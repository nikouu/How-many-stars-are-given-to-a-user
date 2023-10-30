# How many stars given to a user ⭐

Simple site to query how many stars a user has across all their public repos.

Uses the [List repositories for a user API](https://docs.github.com/en/free-pro-team@latest/rest/repos/repos?apiVersion=2022-11-28#list-repositories-for-a-user) and aggregates all the `stargazers_count` values.

An example for this API: https://api.github.com/users/nikouu/repos however check out the code for pagination, as the API will return 30 by default with no pagination. 

The site doesn't use a key, so it's up to the mercy of the rate limiting free GitHub API. 