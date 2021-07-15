**git Alternatives**

**Plastic SCM Steps**

1.1 Setup and install Plastic SCM;

1.2 Plastic for developers option was chosen - Plastic SCM provides a simpler GUI for artists and a more comprehensive GUI for developers;

1.3 The option for a centralized mode was chosen - to provide a different experience than GIT;

1.4 A repository was created with name "CA1" with server devops_21_21_1201770@cloud;

![img_4.png](images/img_4.png)

![img.png](images/img.png)
1.5 A workspace was created with name "CA1";

![img_1.png](images/img_1.png)
1.6 The tut-basic folder was copied to the folder created in the designated path;
___

2.1 To convert the currently private objects(files) to source-controlled items:

![img_2.png](images/img_2.png)
- Move to the "Workspace Explorer" area;
- Right-click the root workspace folder - Select "Add directory tree to source control", this is similar to the "git add " command;

  ![img_3.png](images/img_3.png)
- Right-click the root workspace folder - Select "Checkin" and with all objects selected click the "Checkin" button, this is similar to the "git commit" command;

![img_5.png](images/img_5.png)
___
3.1 Create a new Label:

- Head to Branch Explorer;

![img_6.png](images/img_6.png)

- Right-click the initial checkin we've just made and select "Label this changeset...";

![img_7.png](images/img_7.png)

- Fill in the name Name and Comments sections;

![img_8.png](images/img_8.png)

- The Branch Explorer view now looks like this:

![img_9.png](images/img_9.png)
___
4.1 Creating the new branch for email feature:

- Right-click current changeset and select "Create branch from this changeset...":

![img_10.png](images/img_10.png)

- Input the name and any comments for the new branch:

![img_11.png](images/img_11.png)

- The Branch Explorer view now shows the new branch:

![img_12.png](images/img_12.png)

4.2 Make changes to implementation;

4.3 In the Workspace Explorer view right-click the new Test folder and select "Add to source control":

![img_24.png](images/img_24.png)

4.4 Checkin the changes in the new branch:

- In the Pending Changes view review the differences between the previous file state and the current, if needed, by clicking "Show diff":

![img_13.png](images/img_13.png)
![img_14.png](images/img_14.png)

- Checkin the changes by clicking "Checkin":

![img_15.png](images/img_15.png)
___
5.1 Switch to main changeset (currently v1.2.0):

![img_16.png](images/img_16.png)

5.2 Merge branch into main changeset (currently v1.2.0) by rich-clicking the email-field branch and selecting "Merge from this changeset"

![img_17.png](images/img_17.png)

- Click "Apply Changes":

![img_18.png](images/img_18.png)

- Checkin the changes to the changeset by clicking "Checkin" in the "Pending changes" view:

![img_19.png](images/img_19.png)

5.3 Add label to main:

- In the "Branch explorer" view, right-click the most recent changeset and select "Label this changeset":

![img_21.png](images/img_21.png)
![img_20.png](images/img_20.png)
___
6.1 Create new branch called "fix-invalid-email" by right-clicking the v1.3.0 changeset and selecting "Create branch from this changeset":

![img_22.png](images/img_22.png)

6.2 Input branch name and appropriate comments;

![img_23.png](images/img_23.png)
___
7.1 Switch to main changeset (currently v1.3.0):

![img_25.png](images/img_25.png)

7.2 Merge branch into main changeset (currently v1.3.0) by rich-clicking the fix-invalid-email branch and selecting "Merge from this changeset"

![img_26.png](images/img_26.png)

- Click "Apply Changes":

![img_18.png](images/img_18.png)

- Checkin the changes to the changeset by clicking "Checkin" in the "Pending changes" view:

![img_19.png](images/img_19.png)

7.3 Add label to main:

- In the "Branch explorer" view, right-click the most recent changeset and select "Label this changeset":

![img_27.png](images/img_27.png)
![img_28.png](images/img_28.png)

8.1 Add README info and label "ca1" signifying end of assignement:
- In the "Pending changes" view, click the "Checkin" button;

- In the "Branch explorer" view, right-click the most recent changeset and select "Label this changeset":

![img_29.png](images/img_29.png)
![img_30.png](images/img_30.png)

___