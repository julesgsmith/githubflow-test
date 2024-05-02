Hello There Syntax Squad!

We would like you all to tryout GitHub Flow.
Feel free to make any changes to this file and create a pull request.
Here's the step by step guide.

Use this repo for practice - I just need your GitHub usernames to add you 🙂

Its probably a good idea to go off into 2 groups to give this a go with someone being the coder and someone being the reviewer, then vice versa:

https://github.com/julesgsmith/githubflow-test

To create a new branch off the main branch, the process is as follows: 

**Create a Feature Branch**: Start by creating a new branch from the main branch. This can be done using `git checkout -b feature_branch_name`.

For example:

```powershell
git checkout -b calendar
```

You can now start coding in your new branch

**Work on the Feature**: Once you’ve made changes on this branch, commit your changes locally using `git commit -m "Your descriptive commit message"`.

For example:

```markup
git add.
git commit -m "calendar component added"
```

From here, you want to push your branch so that it goes to the repository, NOT deployment.

**Push the Feature Branch**: Push your feature branch to the remote repository using `git push origin feature_branch_name`.

For example:

```markup
git push origin calendar
```

****Now you need to go into Github > 

In Github, you as the branch creator and pusher of the code, **need to give people permission** to review and comment on the code. 

To do this, you will go into Github and see the following:

![pull main page.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/063beccd-7b00-4a4d-a062-762cf78bed95/pull_main_page.png)

Click on Compare & Pull Request which takes you to the Pull requests page.

Here you need to click New Pull Request

![ppull rewuest page.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/7517bebb-936a-4a56-bef1-360c3210c130/ppull_rewuest_page.png)

On the following page, you need to add the reviewers you would like (see top right hand corner of screen shot):

![add reviewers.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/7ab0c47a-0b9a-4fdb-b1fc-f9a1b75f1845/add_reviewers.png)

**We now switch over to the Reviewers View >**

Go into the Pull requests page and you will see the branch that requires a review

![pull request.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/c4a69683-acfa-40e7-ae7b-47bff5f876b2/pull_request.png)

Click on the open pull request, in this case it is called ‘calendar test’.

Click the button ‘Add Your Review’ 

![review.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/253cacc8-6df3-47d3-8c60-ce10f80a7616/review.png)

You will be taken to the code to see the changes:

![review.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/05f10dff-a9cf-41dd-93af-b143ebd126f6/review.png)

You will be able to add single comments to the code like so (only do this if you don’t have a lot of comments or reviewing to do. It’s actually best practice to ‘Start a review’ by clicking on the button. 

![review.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/2e06b42b-2904-4073-965a-8de078fa0c99/review.png)

So from here, you can review in the GitHub page **OR ‘**Review in codespace’, which takes you to a visual studio browser window. Here you can actually do updates and git add, commit and push origin yourself, however **this should be agreed in advance if you’re going to change someone else’s code.** 

![review.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/3f0533e8-d218-4bec-885e-c7369bbd2289/review.png)

When you’re finished reviewing, you click to submit your review and this will push through to the coder. 

The coder can then review the comments (you may need to refresh the page) and continue with coding in Visual Studio without doing any git pulls. It’s just all still sitting static ready for you to code based off the comments in GitHub. 

You just go through the process again of coding, working off the comments in Github and marking each comment as resolved. 

Once you have finished, you can git add, commit and push origin for a pull request, which will show up below ‘made winnies changes’

![review.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/206627c7-0382-4142-8fce-2cf3edd809fd/review.png)

The reviewer just needs to go back in to review the code and then if approved this time, click approve like below:

![review approved.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/6c871b9b-d473-42f1-b204-36fb52b10cee/review_approved.png)

You will see that it says changes approved and **you the reviewer, or the coder** can merge the pull request so the commits from the branch go into main:

![review approved 2.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/9bb24344-70f6-42b0-b176-dc6a6a67a215/review_approved_2.png)

When ready **Merge the Feature Branch**:

![review merge.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/b7a1ad1d-1dfe-4f42-87fb-18c0c6949356/review_merge.png)

**Delete the Feature Branch**: Once merged, it's a good practice to delete the feature branch to keep the repository clean. 

This can be done using `git push origin --delete calendar`  or you can delete within Github when it prompts you following the merge:

![review delete.png](https://prod-files-secure.s3.us-west-2.amazonaws.com/3e687af6-dccb-4906-bb6e-1f37c85fd130/e6148bed-f4cb-4e90-9dba-526783f0d9ca/review_delete.png)