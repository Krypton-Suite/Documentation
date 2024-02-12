# How to Create a Pull Request

This document will take you through the steps of creating a new pull request. ***Note:*** This document uses the `Standard-Toolkit`, but the procedure is the same for `Extended-Toolkit`.

1) Requirements
    a) A copy of [GitHub Desktop](https://desktop.github.com/)
    b) A copy of either [Standard-Toolkit](https://github.com/Krypton-Suite/Standard-Toolkit) or [Extended-Toolkit](https://github.com/Krypton-Suite/Extended-Toolkit)
    
 ## Steps
 
 **Step 1**
 
 Clone a copy of either [Standard-Toolkit](https://github.com/Krypton-Suite/Standard-Toolkit) or [Extended-Toolkit](https://github.com/Krypton-Suite/Extended-Toolkit) with [GitHub Desktop](https://desktop.github.com/)
 
 ![](https://github.com/Krypton-Suite/Documentation/blob/main/Assets/Miscellaneous/Making%20a%20Pull%20Request/Step%201.png?raw=true)
 
 **Step 2**
 
 Once cloned to your computer, open up GitHub Desktop, navigate to the repository then change the branch from `main` to `alpha`.
 
![](https://github.com/Krypton-Suite/Documentation/blob/main/Assets/Miscellaneous/Making%20a%20Pull%20Request/Step%202.png?raw=true)
 
 (**Note:** You may see different branch names)
 
 **Step 3**
 
 In the same menu as before, click 'New branch', in the new window, create a name for your branch, making sure it is based on `alpha`.
 
 ![](https://github.com/Krypton-Suite/Documentation/blob/main/Assets/Miscellaneous/Making%20a%20Pull%20Request/Step%203a.png?raw=true)
 
 ![](https://github.com/Krypton-Suite/Documentation/blob/main/Assets/Miscellaneous/Making%20a%20Pull%20Request/Step%203b.png?raw=true)
 
 **Step 4**
 
 Once you have made your changes, press the 'Publish branch' button in GitHub Desktop
 
 ![](https://github.com/Krypton-Suite/Documentation/blob/main/Assets/Miscellaneous/Making%20a%20Pull%20Request/Step%204.png?raw=true)
 
 **Step 5**
 
 Once you have published your branch, click 'Preview Pull Request'

![](https://github.com/Krypton-Suite/Documentation/blob/main/Assets/Miscellaneous/Making%20a%20Pull%20Request/Step%205.png?raw=true)

**Step 6**

Once you have clicked 'Preview Pull Request', the following window will appear

![](https://github.com/Krypton-Suite/Documentation/blob/main/Assets/Miscellaneous/Making%20a%20Pull%20Request/Step%206.png?raw=true)

Please ensure that `alpha` is selected ***before*** clicking 'Create pull request'

**Step 7**

Once you have clicked 'Create pull request', GitHub Desktop will launch your default web browser. From there, please type in your notes, then assign either `@Smurf-IV` or `@Wagnerp` before clicking 'Create pull request'. From there, we will review your changes, and sometimes ask you to make changes if necessary. Once the changes are merged, please then delete your branch to avoid "stale branches".

![](https://github.com/Krypton-Suite/Documentation/blob/main/Assets/Miscellaneous/Making%20a%20Pull%20Request/Step%207.png?raw=true)

***Additional Notes***

1) Please remember to always update `Changelog.md` with any changes that you have made. This is located in ***Documents\Help\Changelog.md***.

2) We ask you to provide a build report when submitting a pull request. This allows us to verify that there are no errors within the code. To do this, simply execute `run.cmd` from the root directory. Choose option '4' -> '1'. Once completed, it should show something like this:
    
    ![](https://github.com/Krypton-Suite/Documentation/blob/main/Assets/Miscellaneous/Making%20a%20Pull%20Request/Build%20Log%20Example.png?raw=true)

   Simply take a snippet of the log, then paste it into your pull request description.
 