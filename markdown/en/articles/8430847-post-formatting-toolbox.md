# Post formatting toolbox

> How fields where posts can be made can be formatted

The same formatting rules apply for the different posts around Catenda Hub. Posts can include topic descriptions, comments approval descriptions and approval comments. Variations can apply with the different access to who can edit the post. Catenda uses markdown to format text. This means that certain characters before and after sentences will affect the styling of the text. This is what a topic header and descriptino can look like after they are submitted:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/01-intro.png)

## 1. Formatting availability

It is often possible to tell that submitted fields can be formatted by the toolbox that appears below the field when the field is edited.

> **Note:** Zoom far enough out with the browser zoom scale to see all tools.

Formatting is available in the following fields:

### 1.1 **Topic Description and comment**

Edit the description or comment of an existing topic or when submitting a new topic to see the toolbox:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/02-topic-description-and-comment.png)

### 1.2 **Approval request description**

While the toolbox does not apppear in the description of the new approval request dialogue formatting does get applied to this description.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/03-approval-request-description.png)

> **Note:** This field cannot be edited after submitting the approval request.

### 1.3 Topic board description

While the toolbox appears in the new topic board description it is important to note that the description is not formatted when the board is submitted.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/04-topic-board-description.png)

## 2. **Topic comment attachment**

In topic comments the an attachment tool is visible. Click the + button in a topic to add an attachment.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/05-topic-comment-attachment.png)

Click [here](https://support.catenda.com/en/articles/8053352-topic-body-the-content-of-a-topic#h_0e3c0059ae) to read more about comment attachments.

## 3. **Styling text**

The following methods allow you to style your text:

### 3.1 **Bold, italics, strikethrough**

Bold italics and strikethrough styling can be done in any part of a line and works well together with other styling that has to be at the start of a line.

<img alt="**This will be bold** __This will also be bold__ *This will be italics* _This will also be italics_ **This will be bold _combined with italics_** ~~This text will be struck through~~" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-b49c2f10b2de.png" width="290"/>   \<->   <img alt="This will be bold​This will also be bold​This will be italics​This will also be italics​This will be bold combined with italicsThis text will be struck through" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-ea38fb93f8ee.png" width="290"/>

### 3.2 **Headers**

The header tool applies hastags/pound signs to the beginning of the line. There are 5 levels of headers that are supported: The formatting that the header receives is dependent on the amount of hashtags/pound signs (`#`) that are at the beginning of the line.

<img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-c21079ec7efb.png" width="290"/>   \<->   <img alt="" src="https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/inline-557784a5d702.png" width="290"/>

### 3.3 **Links**

Link styling can be done in any part of a line and works well together with other styling that has to be at the start of a line. Links in descriptions will be green and underlined. Their text can be different than the url that the link points to. Urls will be automatically turned into clickable links

```
https://hub.catenda.com
```

will become [https://hub.catenda.com](https://hub.catenda.com) and

```
[Catenda Hub](https://hub.catenda.com)
```

will become: [Catenda Hub](https://hub.catenda.com)

> **Note:** Be careful when clicking on links as even though the text [from the brackets] might show one link, the actual link (from the parantheses) might be different. It is recommended to hover over a link and look at where the browser will redirect to before clicking a link.

### 3.4 **Preventing formatting**

By wrapping words in non letter of number characters you can make them look different. This is not always desired. If you put a `\\` in front of such a character, the `\\` will disappear. Any formatting that would have been applied for these characters will then stop working. If you put a `\\` on an empty line that is not part of a [list](#h_6da4949f8c) the result will still be an empty line as well.

## 4. **Breaking up text and adding structure**

The following methods let you enhance your text by breaking it up and adding structure:

### 4.1 **Images**

Images in descriptions can have a link attached to them. To embed images you can use this syntax

```
![text](https://bimsync.com/img/favicon/dark-mode/favicon-32x32.png)
```

to get this image with the word text behind it.

![text](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/06-images.png)

In order for the image to properly show up, Catenda has to have access the link that is provided.

> **Note:** \+ The image can be added to a description \+ The image can be mixed with text so you can have text both before, and after the image in the same comments or description. \+ Images like these can be combined with tables and lists. For example you could add a checkmark image in the middle of a sentence/table instead of the formatting checkbox which only works at the beginning of a sentence \- You cannot guarantee that the link to the image stays available in the future.

_Getting a Catenda image document link_ If you right click the [download action button after selecting a document](https://support.catenda.com/en/articles/4670288-actions-in-the-document-structure#h_133e2bcc57) or right click the [download latest revision action button after having opened a document](https://support.catenda.com/en/articles/9323521-actions-in-a-document) you can copy the download link of the document. If you use this link in your topic like above, you will be able to use Catenda documents in topics.

> **Note:** \+ If you add a link to a Catenda image document you can add images that only show on Catenda and are not available in other platforms that the topic may be exchanged with. \+ By adding links to a Catenda image document only people with access to the document will see the image. \- If you add a link to a Catenda image document it will not be visible in other platforms that the topic may have been synchronized with and to people that do not have access to the document.

### 4.2 **Lists**

**Unordered lists** Start an unordered list with a blank line above it, then either hyphen (`-`), plus (`+`), or an asterix (`\*`) followed by a space. Insert 4 spaces or a tab space at the start of the line to create a sublist.

```
 - First element - Second element     - Insert 4 spaces at the start of the line to create a sublist.
```

Or

```
 + First element + Second element     + Insert 4 spaces at the start of the line to create a sublist.
```

Or

```
 * First element * Second element     * Insert 4 spaces at the start of the line to create a sublist.
```

Will all turn into this:

- First element
- Second element
    - Insert 4 spaces at the start of the line to create a sublist.

> **Note:** In order for an unordered list to be formatted correctly there needs to be  a blank newline on the line above the list.

**Ordered lists** Start an ordered list with a blank line above it, a number, a period and a space (`1. `) What the number in front is, does not matter, just that it’s a number followed by a period. Insert 4 spaces or a tab space at the start of the line to create a sublist.

```
1. item one 2. item two 3. item three     4. item four
```

Or

```
1. item one 1. item two 1. item three     1. item four
```

Or

```
1. item one 10. item two 1. item three     1000. item four
```

Will all turn into this:

1. item one
1. item two
1. item three

    4. Item four

> **Note:** In order for an ordered list to be formatted correctly there needs to be  a blank newline on the line above the list.

The number you start with does not affect where the numbering begins

```
23. twenty-three 1. twenty-four 1. twenty-five     1. twenty-six
```

Will turn into:

1. twenty-three
1. twenty-four
1. twenty-five

    4. twenty-six

If you wish to reset the numbering and start from one again on a second list within the same post you can put a blank or a [divider](#h_3a36cfbc61) in between.

To [make sure the list does not get formatted](#h_2ec17c688b) so you can use your own numbering: Put a character on the line above the list. A good choice is `\\` because it will disappear.

```
\23. twenty-three 24. twenty-four 25. twenty-five     26. twenty-six
```

Put a backslash (`\\`) before the period (`.`):

```
23\. twenty-three 24\. twenty-four 25\. twenty-five     26\. twenty-six
```

Will all turn into:

23\. twenty-three 24\. twenty-four 25\. twenty-five 26\. twenty-six

### 4.3 **Dividers**

Three dashes `---` or more on their own line will create a divider:

---

### 4.4 **Checklists**

These can be checked in the description of a topic. _Access required:_ Write access to the topic board.

```
- [ ] first item - [x] second item     - [ ] sublist item
```

Will turn into this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/07-checklists.png)

Click [here](https://support.catenda.com/en/articles/5036461-check-lists-within-issues) to watch a quick video on how checklists can be used in the project. If you write` - [ ]` or `- [x]` the box will still appear unchecked and checked when the comment is submitted or saved after editing.

**Checkboxes in comments** In comments checkboxes can only be checked through formatting. Checkboxes in comments cannot be clicked to be checked. _Access required -_ The comment creator has access to the editing of the created comment

### 4.5 **Tables**

Text in descriptions can be ordered in tables.

```
|            | Windows            ||             | |            | Type 1   | Type 2   | Sum total   | |----------- | -------- | -------- | ----------- | | **Price**  | 500,-    | 400,-    |             | | **Amount** | 10       | 4        |             | | **Sum**    | 5 000,-  | 1 600,-  | **6 600,-** |
```

will result in this

<div class="intercom-interblocks-table-container"><table role="presentation"><tbody><tr><td><p></p></td><td><p class="intercom-align-right">Win</p></td><td><p>dows</p></td><td><p></p></td></tr><tr><td><p></p></td><td><p>Type 1</p></td><td><p>Type 2</p></td><td><p>Sum total</p></td></tr><tr><td><p><b>Price</b></p></td><td><p>500,-</p></td><td><p>400,-</p></td><td><p></p></td></tr><tr><td><p><b>Amount</b></p></td><td><p>10</p></td><td><p>4</p></td><td><p></p></td></tr><tr><td><p><b>Sum</b></p></td><td><p>5 000,-</p></td><td><p>1 600,-</p></td><td><p><b>6 600,-</b></p></td></tr></tbody></table></div>

### 4.6 **Code blocks**

You can insert single lines of code like this: Two `\`` surrounding text will look like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/08-code-blocks.png)

Three backticks `\`\`\`` above and below a bit of text will look like this:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/09-code-blocks.png)

It is not possible to add tables in code blocks

### 4.7 **Markdown dialect**

If you would like to know more about how text is formatted in comments and descriptions we use the markdown dialect "flexmark" to format this text. Find out more about flexmark on their [github page](https://github.com/vsch/flexmark-java).

## 5. **@ Mentioned members and teams**

Click the `@` tool or write `@` in a description or comment to mention a member. After typing `@` a dropdown list of members and teams is displayed.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/10-mentioned-members-and-teams.png)

Search through the list by starting to type the email, member name or team name. Go up and down the list with the arrow keys and click or press enter to select a member or team. For a member or team to appear in this list the member or team has to at least have read access to the topic board. After selecting a member or team in the list the `@` will get some extra text that can look like:

`@[\<email address of member>]` or `@[\<Team name>]`

### 5.1 **Saving or submitting a mention in a topic**

When the description is saved or the comment is submitted related members with access to the topic board recieve a notification. If the member email or the name of the team is known it can also be written manually but if they are not part of the topic board the related members will not be notified that they are mentioned.

**Notification upon member mention** Members with access to the topic board that are mentioned receive a notification that they are mentioned in a topic.

**Notification upon team mention** Members with access to the topic board that are part of a team that is mentioned receive a notification that a team they are part of is mentioned in a topic.

**Notifications about future topic events** Members of teams that are mentioned in topic descriptions and comments only receive the one notification upon the saved description or submitted comment.

In addition to the notification that they are mentioned, members that are mentioned in posts are automatically set to [follow](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_a97f3b264e) the topic and will get notifications about topic events like new comments and status changes. This is a great way to ensure that more than just the [assignee](https://support.catenda.com/en/articles/8400566-issue-header#h_0a91fa8dd9) and [requestee](https://support.catenda.com/en/articles/8400566-issue-header#h_1aea0990a7) get notifications about future changes an topic. If a member no longer wishes to follow the topic they have to manualy unfollow it.

### 5.2 **Mention in post**

Mentions in posts can be identified by having green text color.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/11-mention-in-post.png)

In the background the unique id of the mentioned project participant is saved. It is the name of the participant that is displayed in this green text. Even if the member or team changes name, they will stay mentioned in the post but under their new name.

Mentioned members have a clickable link that directs to the [member page](https://support.catenda.com/en/articles/8228836-member-page) of that member. Mentioned teams have clickable link that directs to the [team page](https://support.catenda.com/en/articles/7891755-team-page) of that team.

**Non-existing member** If there is no member in the project that has the email address that is mentioned the post looks like this instead:

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/12-mention-in-post.png)

This can either be because the email was formatted wrongly of because the member is no longer part of the project. Should a member with this email address become part of the project in the future, the post changes to displaye the name of that member.

**Non-existing team** If a team has been removed from the project and a new team is created, this new team will not be mentioned. To mention the new team the post has to be re-submitted.

## 6. **# Tagged topics**

Click the `#` tool or write `#` in a description or comment to tag a topic. After typing `#` a dropdown list of topics from all topic boards is displayed.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/13-tagged-topics.png)

Search through the list by starting to type the title or topic number. Go up and down the list with the arrow keys and click or press enter to select a topic. For a topic to appear in this list the member that is tagging has to have access to the board that the topic is in. After selecting a topic in the list the `#` will get some extra text that can look like:

`#[\<topic number>]`

### 6.1 **Saving or submitting a tagged topic**

When the description is saved or the comment is submitted a topic relation is created. The linked topic is then added to the list of [linked topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) in [the right menu](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue) of the topic.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/14-saving-or-submitting-a-tagged-topic.png)

In addition to the topic where anohter topic was tagged, the tagged topic itself recevieves a link back to the topic where it was added to the list of [linked topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) in [the right menu](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue).

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/15-saving-or-submitting-a-tagged-topic.png)

The topic link can later be removed from either the topic with the tagged topic in the description or form the topic that was tagged by going to each topic and editing the list of [linked topics](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue#h_edf2cb07a8) in [the right menu](https://support.catenda.com/en/articles/8053299-right-panel-in-an-issue).

### 6.2 **Tagged topic in post**

Tagged topics can be identified by first having a circle with the color of the current status of the tagged topic along with the name of that status. After that the topic title is shown followed by the topic number.

Together with the checkboxes, tagged topics that are closed count towards the progress in the progress bar that is displayed towards the top while tagged topics that are open count towards the total items the progress is counted towards.

![](https://raw.githubusercontent.com/catenda/help-center/main/images/tt9y4c9z/16-tagged-topic-in-post.png)

Tagged topics have a clickable link that opens the tagged topic in its topic board.
