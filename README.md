## Operations-workflow-automation
Built an automated workflow to manage call forwarding requests using Notion, n8n, Tally, and Telegram.

## Problem
Call forwarding requests were being managed manually through messages, making it difficult to track schedules, ownership, and completion status.

## Solution
Created an end-to-end automation system that:
Captures requests through Tally forms
Creates tasks automatically in Notion
Generates standardized forwarding messages
Sends notifications at the scheduled time
Prevents duplicate notifications
Updates task status automatically after execution

## Workflow
Tally Form → n8n Webhook → Notion Dashboard → Wait Until Scheduled Time → Telegram Notification → Update Task Status

## Tools Used
n8n
Notion
Tally
Telegram

## Features
Automated task creation
Scheduled notifications
Status tracking
Duplicate prevention
Centralized dashboard

