# LeetCode Reminder Workflow

Welcome to the **LeetCode Reminder Workflow** template repository! This project provides a GitHub Actions workflow that automatically reminds contributors to solve LeetCode problems regularly. Use this template to set up automated reminders in your own repositories, track problem-solving progress, and encourage consistent practice.

## Features

- **Automated Reminders**: Sends scheduled notifications to repository contributors to solve LeetCode problems.
- **Customizable Schedule**: Easily adjust the frequency (daily, weekly, etc.) of reminders.
- **Progress Tracking**: Optionally track solved problems and display them in your repository.
- **Easy Setup**: Clone or use as a template with minimal configuration.

## Getting Started

### 1. Use as Template

Click the `Use this template` button on GitHub to create a new repository based on this workflow.

### 2. Configure Workflow

1. Update the workflow YAML file (usually in `.github/workflows/leetcode-reminder.yml`) to match your desired schedule and notification method.
2. Optionally, adjust environment variables and settings to customize the reminder message, users to notify, and other preferences.

### 3. Enable GitHub Actions

Make sure GitHub Actions is enabled for your repository. The workflow will run based on the defined schedule.



> **Note:** You may need to adjust permissions and target issue numbers or notification channels as per your needs.

## Customization

- **Frequency:** Change the `cron` expression to set reminders (see [Cron syntax](https://crontab.guru/)).
- **Message:** Update the reminder message in the workflow script.
- **Notification Target:** Configure who receives reminders (e.g., issue comments, pull requests, Slack, email).

## Contributing

Contributions are welcome! Feel free to submit issues, feature requests, or pull requests to improve the workflow or add new features.

## License

This template is released under the [MIT License](LICENSE).

## Support

If you have questions or need help setting up your workflow, please open an issue in this repository.

---

Happy Coding and Good Luck on LeetCode! 🚀
