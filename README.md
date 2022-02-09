# Testing Git Actions

## **Merge Schedule (gr2m/merge-schedule-action)**

Workflow file: `.github/workflows/merge-schedule.yaml`

In your pull requests, add a line to the end of the pull request description:

```
/schedule 2022-01-31
```

Or if you need a more precise, timezone-safe setting, you can use an ISO 8601 date string:

```
/schedule 2022-01-31T12:00:00.000
```

#### Links:
- [Actions Merge Schedule](https://github.com/marketplace/actions/merge-schedule)
- [Cron](https://crontab.guru/every-hour)
- [Automatically schedule a git merge using GitHub Actions](https://www.sean-lloyd.com/post/schedule-git-merges-with-github-actions/)
