# Custom Rules starter pack for OpenAI dots

Copy-paste Custom Rules to set safe boundaries for your dot before you connect your accounts.

> **Community suggestions, not official guidance.** Your dot can make mistakes, including when following your rules. Review consequential work. Rules add boundaries on top of OpenAI's built-in safeguards; they never replace them.

## How Custom Rules work

On mobile, open your dot's profile → **Customize → Custom rules**. Describe the action the rule covers, then choose one of four behaviors ([OpenAI Help](https://help.openai.com/en/articles/20001530-getting-started-with-your-dot)):

| Behavior | Meaning |
| --- | --- |
| **Take action without asking** | The dot just does it. |
| **Take action if pre-approved** | Only if you explicitly asked for this action in your prompt. |
| **Ask before taking action** | The dot asks for approval every time. |
| **Hand off to you** | The dot stops and you finish it yourself. |

### What rules can't change

Per OpenAI's [privacy, security and safety FAQ](https://help.openai.com/en/articles/20001529-dots-privacy-security-and-safety-faqs):

- Changing a password or transferring money always hands off to you.
- Permanently deleting data or installing software may require approval each time.
- Auto-review and safety monitoring can't be turned off.
- Proactive research (background work) can't send messages, change content through plugins, or control a browser or computer.

## Safe starter set

If you only add five rules, add these. Loosen them once you trust your dot.

| Rule (paste as the description) | Behavior |
| --- | --- |
| Sending any email, message or chat to another person | Ask before taking action |
| Making any purchase or starting a subscription | Hand off to you |
| Deleting files, emails, events or records | Ask before taking action |
| Sharing a document, link or file with anyone outside my account | Ask before taking action |
| Accepting terms, invitations, or granting app permissions | Hand off to you |

## Rules by area

### Email and messaging

| Rule | Behavior |
| --- | --- |
| Reading and summarizing my inbox | Take action without asking |
| Drafting replies and saving them as drafts | Take action without asking |
| Sending a reply I asked for in my prompt, to the recipient I named | Take action if pre-approved |
| Sending messages to anyone I haven't emailed before | Hand off to you |
| Posting in Slack or Teams channels (not DMs to me) | Ask before taking action |
| Replying on my behalf in group chats | Hand off to you |

### Calendar

| Rule | Behavior |
| --- | --- |
| Reading my calendar and summarizing my day | Take action without asking |
| Adding private reminders or focus blocks to my own calendar | Take action without asking |
| Accepting, declining or rescheduling meetings | Ask before taking action |
| Sending invites to other people | Take action if pre-approved |

### Money and purchases

| Rule | Behavior |
| --- | --- |
| Comparing prices and building a shopping list | Take action without asking |
| Buying a specific item I named, up to the price I stated | Take action if pre-approved |
| Any purchase I didn't explicitly request | Hand off to you |
| Starting, upgrading or cancelling subscriptions | Hand off to you |

### Files and documents

| Rule | Behavior |
| --- | --- |
| Creating new documents, notes and drafts | Take action without asking |
| Editing documents I created with my dot | Take action without asking |
| Editing documents other people own or share with me | Ask before taking action |
| Moving or renaming files in shared folders | Ask before taking action |

### Code (Codex)

| Rule | Behavior |
| --- | --- |
| Opening Codex tasks and preparing pull requests | Take action without asking |
| Merging pull requests or pushing to the main branch | Hand off to you |
| Deploying to production or changing infrastructure | Hand off to you |
| Commenting on issues or PRs in public repositories | Ask before taking action |

### Accounts and privacy

| Rule | Behavior |
| --- | --- |
| Changing account settings, notification settings or profiles | Hand off to you |
| Sharing my personal details (address, phone, ID) with a website or person | Hand off to you |
| Filling in forms on websites | Ask before taking action |
| Posting publicly on social media | Hand off to you |

## Tips

- **Be specific when you pre-approve.** Say who a message goes to, what it says, and when or under what conditions to send it. Approving one message doesn't give ongoing permission ([OpenAI Help](https://help.openai.com/en/articles/20001529-dots-privacy-security-and-safety-faqs)).
- **Start with one job.** Connect only the apps that job needs, then expand.
- **Disconnecting an app doesn't delete what your dot learned from it.** Only resetting (deleting) your dot does.
- **Watch Activity View** in the desktop app for the first few days, including background tasks.
- **Be careful with text messages.** Texting uses a third-party provider; avoid sending sensitive information by text.

## Contributing

Have a rule that saved you? Open a PR with the rule, the behavior, and a one-line reason.
