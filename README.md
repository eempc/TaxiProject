# Group 2 Taxi Project Readme

The master branch has been seeded with the *taxi-company-stage-one* project. None of the files have been changed from the original BlueJ project.
 
## Collaborators

Evelyn, Jack G, Kimberley, Alexander

## Textbook questions quick reference

Pages 562 to 569 are in TextbookPages.pdf

> Here is a possible series of development steps for the taxi company application - Page 562
>* Enable a single passenger to be picked up and taken to her destination by a single taxi 
>* * KM: *(complexity of this looks ok)*
>* Provide sufficient taxis to enable multiple independent passengers to be picked up and taken to their destinations
 concurrently.
>* * KM: *(this should be broken down into further development steps to break down the build work)*
>* Enable a single passenger to be picked up and taken to his destination by a single shuttle
>* * KM: *(complexity of this looks ok)*.
>* Ensure that details are recorded of passengers for whom there is no free vehicle
>* * KM: *(complexity of this looks ok but there's a step missing in the development work for "enable a single passenger to request a pickup")*.
>* Enable a single shuttle to pick up multiple passengers and carry them concurrently to their destinations
>* * KM: *(complexity of this looks ok but we might need to add functionality to allow a passenger to specify if they want "pooled" with other passengers or if they want to ride alone)*.
>* Provide a GUI to display the activities of all active vehicles and passengers within the simulation 
>* * KM: *(complexity of this is high)*.
>* Ensure that taxis and shuttles are able to operate concurrently
>* * KM: *(I think this is in the wrong order and should be completed after step 1)*.
>* Provide all remaining functionality, including full statistical data 
>* * KM: *(too vague, complexity too high, needs broken down further and specified)*.

 > **Exercise 16.17** Critically assess the list of steps we have outlined, with the following questions in mind. Do
> you feel the order is  appropriate? Is the level of complexity of each too high, too low, or just right? Are there
> any steps missing? Revise the list as you see fit, to suit your own view of the project

> **Exercise 16.18** Are the completion criteria (tests on completion) for each stage sufficiently obvious? If so document some tests for each.

> **Exercise 16.19** If you have not already done so, take a thorough look through the implementation in the taxi-company-stage-one project. Ensure that you understand how movement of the taxi is effected through its act method.

> **Exercise 16.20** Do you feel that the TaxiCompany object should keep separate lists of those vehicles that are free
> and those that are not, to improve the efficiency of its scheduling? At what points would a vehicle move between the lists?

> **Exercise 16.21** The next planned stage of the implementation is to provide multiple taxis to carry multiple
> passengers concurrently. Review the TaxiCompany class with this goal in mind. Do you feel that it already supports
> this functionality? If not, what changes are required?

> **Exercise 16.22** Review the way in which vehicle:passenger associations are stored in the assignments??? map in
> TaxiCompany. Can you see any weaknesses in this approach? Does it support more than one passenger being picked up from the same location? Could a vehicle ever need to have multiple associations recorded for it?

> **Exercise 16.23** If you see any problems with the current way in which vehicle:passenger associations are stored
>, would creating a unique identification for each association help, say a ???booking number???? If so, would any of the
> existing method signatures in the Vehicle hierarchy need to be changed? Implement an improved version that supports the requirements of all existing scenarios.

> **Exercise 16.24** Review the tests implemented in the test classes of taxi-company-stage-one. Should it be
> possible to use these as regression tests during the next stages, or would they require substantial changes?

> **Exercise 16.25** Implement additional tests and further test classes that you feel are necessary to increase your
> level of confidence in the current implementation. Fix any errors you discover in the process of doing this.

## Git quick guide

After you've installed Git onto your computer, start up a bash terminal in the folder where you will work on.

1. Click the "master" dropdown tab at the top left of the repository of this page
2. Type in a name for the branch, e.g. "my-feature-branch"
3. Click the create branch button
4. On git bash, type the following:
    1. `git clone https://github.com/eempc/TaxiProject`
    2. `git checkout -b <your branch name> origin/<your branch name>`
5. Start making coding changes
6. Commit your changes by:
    1. `git add <file>`
    2. `git commit -m "<commit message>"`
7. When done, type `git push origin` to push changes to the repository
8. Create a Pull Request and wait for approval (pending release branch)