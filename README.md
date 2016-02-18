# DoorDash-Slack (Unsupported)

*Currently unavailable, will update with link to Slack app directory sometime in the future.*

![Screenshot](/screenshot1.png?raw=true "Screenshot")

## Overview

DoorDash-Slack enables [DoorDash](https://www.doordash.com/) customers to invite [Slack](https://slack.com/) team members to join in on group orders and track their progress.

## Usage

1. Click: <a href="https://slack.com/oauth/authorize?scope=commands,bot&client_id=3764086579.21683142530"><img alt="Add to Slack" height="40" width="139" src="https://platform.slack-edge.com/img/add_to_slack.png" srcset="https://platform.slack-edge.com/img/add_to_slack.png 1x, https://platform.slack-edge.com/img/add_to_slack@2x.png 2x"></a>


2. If you'll be using DoorDash-Slack in a private channel, you'll need to invite the `@doordash` user to the channel first: `/invite @doordash`

3. Create a group order on [DoorDash](https://www.doordash.com/) by clicking the "Create a group order" link on the top right of a restaurant page on the web. You will receive a link to share.

4. Share the group order in a channel: `/doordash <link> 5:00pm`. The time is the intended checkout time.

5. Team members will be able to follow the link and add items to the cart. You will receive a reminder in the channel 10 minutes before the intended checkout time.

6. At the intended checkout time, `@doordash` will remind you to check out your cart.

7. You and your teammates will receive status updates in the channel through the course of the delivery!

## Contributors

This is a hackathon project by Jason Jong and Mitchell Koch.
