---
url: https://wiki.hornbill.com/index.php?title=Project_RAG_Tolerance_Matrix
---

# Project RAG Tolerance Matrix
Introduction Create matrices for the automatic calculation of the overall project RAG status based on weightings assigned to the individual project elements. Individual Red, Amber, and Green tolerances are assigned to one or more of the individual project elements (Benefits, Cost, Quality, Risk, Time). Multiple matrices can be created in Hornbill Administration. A matrix is associated to a Project via the "Project Settings" tab which can be accessed within each Project. 

## Creating Project RAG Tolerance Matrices

Select the **+** icon on the left most table to create a new matrix

* Name - Provide the name of the new matrix
* Status - The status of the new matrix

Select **Create** to add.

Repeat this process as needed to add more rag tolerance matrices.

Once created and selected, rules and weightings will appear in the two tables on the right hand side of the page. The rules for red, amber and green are created automatically and cannot be deleted. Only the red and green rule scan be edited. No new rules can be added. Editing the red or green rule will automatically update the amber rule.

## Managing Project RAG Tolerance Matrices

Edit and remove matrices, by selecting either the **Pencil** or **Trash Can** icons next to the matrix you wish to edit or remove.

* Removing a matrix will have an impact on automatic project rag status calculations for each project defined to use that matrix.

  
Select the **+** icon on the bottom right table to create a new weighting

* RAG Tolerance - The specified rag tolerance
* Red Weighting - The weighting value of a red status for the specified rag tolerance
* Amber Weighting - The weighting value of an amber status for the specified rag tolerance
* Green Weighting - The weighting value of a green status for the specified rag tolerance
* Status - The status of the weighting. If this value is not set to Active it will not be factored into the weighting calculations

## Using a Project RAG Tolerance Matrix

Automatic calculation of the overall project RAG status is enabled via the Project Settings panel accessed in a project. This is where the preferred matrix is also specified. Once enabled, any adjustment to RAG status of the individual project elements ( i.e. Benefits, Cost, Quality, Risk, Time) included in your matrix will influence the overall project RAG status.