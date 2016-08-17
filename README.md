# Solving Your First Lab

Now that you've got the Learn IDE up and running, you're going to use it to solve your very first lab on Learn. 

## Objectives

1. Open a lab by clicking "Open" on this page on Learn.co
2. Run the lab's tests with the `learn` CLI command
3. Make a change to your copy of this lab
4. Pass the tests using the `learn` CLI command
5. Submit the passing lab with the `learn submit` CLI command

## Instructions

In this this lesson you will practice the workflow that allows you to solve labs on Learn.

### 1. Opening a Lab

Click on the "Open" link on the lab toolbar above.

![Open](https://s3.amazonaws.com/learn-verified/LearnOpen.png)

After you click on this, your Learn IDE will launch with the lab opened and ready for you to work on.

### 2. Exploring the Lab in the IDE

You should see all of the files associated with this lab in the Learn IDE's file browser on the left pane.

![lab-fail](http://learn-co-videos.s3.amazonaws.com/welcome/first-lab-setup.png)

### 3. Running the Tests

In the console on the bottom pane, run the test suite by typing `learn` and hitting enter. 

You'll see something similar to:

![lab-fail](https://s3.amazonaws.com/learn-verified/LearnRunningLearrn.png)

You can see your test is currently failing, which is fine. We haven't done any work yet, so it makes sense.

The failure reads: `Make sure you have edited the file edit-me.txt`

Test-Driven Development (TDD) is powerful workflow the best professional developers use everyday to build software. Every lab on Learn provides you with a test suite to make pass by reading error messages and understanding software specifications. As you work on Learn, you are mastering a powerful workflow that will be crucial to your success as a developer.

You should always be reading the test output as it will direct you on what you need to program to pass the lab.

You can always read the test code in the `spec` directory of a lab, just ignore any files called `spec_helper.rb` or in `support` directories and focus on the test files, for example, in this lab, reading the file `spec/first_lab_spec.rb` will provide some insight into the requirements of the lab.

### 4. Passing the Lab

To pass this lab, make any change to the content of the `edit-me.txt` file. You can do this by clicking on the name of the file in the file browser in the left pane; its contents will load in the text editor. Type into the text editor to change the contents of the file, then save your changes. When you've done that, running `learn` should show you a passing test suite.

![Passing Lab](http://learn-co-videos.s3.amazonaws.com/welcome/passing-test.png)

### 5. Submitting the Lab

Once your local tests are passing, you can submit this lab by running `learn submit` from your terminal.

![learn-submit](https://s3.amazonaws.com/learn-verified/LearnSubmit2.png)

You should see this lab pass on Learn.co (if you don't, try hitting refresh, if you still don't, "Ask a Question" and we'll help). Congratulations! You've just solved your first lab. 

## Video Demo

<iframe width="100%" height="720" src="https://www.youtube.com/embed/R-G9JuXDuCk?rel=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>
