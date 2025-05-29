# Roddit
A bare-bones Reddit clone for learning purposes.
---
<h3> Possible actions </h3>
<ol>
  <li> Create a new user</li>
  <li> Login as a new user</li>
  <li> Make a new Subroddit</li>
  <li> Make a Post in a Subroddit</li>
  <li> Comment on a post</li>
  <li> Upvote/downvote a post</li>
  <li> If you are a Moderator of a Subroddit, you can make someone else a Moderator or revoke his privilege</li>
  <li> You can report a post as inappropiate </li>
  <li> You can see all comments on a post</li>
  <li> You can see all posts on a sub</li>
</ol>

<h4> Java classes used: </h4>
<ol>
  <li> User </li>
  <li> Post </li>
  <li> TopLevelPost, extending Post </li>
  <li> Vote </li>
  <li> Roddit (context info) </li>
  <li> Subroddit </li>
  <li> Report </li>
  <li> Feed (what an user seed) </li>
  <li> Various services </li>
</ol>
<h4> Tables in the database: </h4>
User, Post, Subroddit, Vote, Mod(in progress).
Post holds foreign keys, to User and Sub, Vote holds Foreign Keys to User and Post.
