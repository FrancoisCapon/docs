---
title: "User Management" 
sidebar: katalon_studio_docs_sidebar
permalink: katalon-analytics/docs/user-management.html 
redirect_from:
    - "/display/KA/User+Management/"
    - "/display/KA/User%20Management/"
    - "/x/lQjR/"
    - "/katalon-analytics/docs/user-management/"
description: How to manage Users at organization and team level
---
Each role has permission at the organization or team level exclusively.

## Invite a user to the organization

* Only the organization **Owner** or **Admin** can invite a user to the organization.
* From Katalon TestOps dashboard, select an organization.
* From **Users** tab, select **Invitations** tab.
* Enter an email address and click **Invite**.
* Copy the activation link and send it to that person.

![](https://github.com/katalon-studio/docs-images/raw/master/katalon-analytics/docs/user-management/KT-user-mgt-invitation.png)

The invited person accepts the invitation by clicking the activation link directing to Katalon TestOps and then clicking the name of the organization.
Before that person accepts the invitation, their email address will be listed in **PENDING INVITATIONS**. Once the person joins the organization, their name and email address will be shown below the **Users** tab with the default User role. 

The new user can only access projects when added by the team Owner or Admin to a team.

> Notes: The Owner/Admin can withdraw the invitation by removing it from **PENDING INVITATIONS**.

## Invite a user to the team

* Only the team **Owner** or **Admin** can invite a user to the team.

> Note: Only the user in an organization can be invited to a team in that organization. 

* Select a team, from **Users** tab in a team, select that person's email in the drop-down list and then click **Add** to add a user to a team. 
* The default role for the invited person is **User**.

## Remove existing user from organization or team

Select your organization/team > from **Users** tab, click the remove icon in the last column and confirm your action in the pop-up. 

* The User that is removed from the organization can be re-invited by the Organization Owner or Admin. Refer to *Invite a user to the organization*.
* The User that is removed from the team can be re-added to work on projects. Refer to *Invite a user to the team*.

## Assign Admin or User role to the existing team member

The Admin and Owner can reassign the existing Admin and User to a new role. Select your organization/team > from **Users** Tab, click the pencil icon in the last column and then select **Admin** or **User** role in the drop-down list. A user can have different roles in different teams.

## Assign Billing Manager role to the existing team member

**Billing Manager** role is only available at the organization level and granted by the organization Owner or Admin. Select your organization > from **Users** Tab, click the pencil icon in the last column and then select **Billing Manager** role in the drop-down list.

## Transfer organization ownership to the existing team member

The Owner and Admin of an organization can transfer the ownership of an Owner to another existing team member. 

* Select an organization > select **Users** tab > search for the target user to assign the **Owner** role.

* Click the pencil icon in the last column and then select **Owner** in the drop-down list.

* Click **Save**.

> Note: Transferring Organization ownership does NOT affect Team ownership. The previous Owner still has full permission as a Team Owner to those teams having been created by them before.

## Transfer team ownership to the existing team member

The Owner of a team can transfer the ownership to another existing team member. 

* Select a team > under **Users** tab, search for the target user to assign the **Owner** role.

* Click the pencil icon in the last column and then select **Owner** in the drop-down list.

* Click **Save**.
