### READ ME / INSTRUCTIONS ###

- This .md file contains the setup instructions for Cursor, including creating PRD, .cursorrules, etc. 
- Before starting any develoopment work, ensure you have the below files fully populated
-- product-requirements-doc-prd.md
-- .cursorrules
-- @project-plan-pp.md
-- @project-log-pl.md

### INSTRUCTIONS FOR PRODUCT REQUIREMENTS DOC (PRD) SETUP ###

- Use https://claude.ai/project/6edd6e3c-fb95-4175-916d-9d0d48f81b88 to create a Product Requirements Document (PRD) for the project
- Once complete, input the PRD into @product-requirements-doc-prd.md file

### INSTRUCTIONS FOR PROJECT PLAN (@PROJECT-PLAN-PP.MD) FILE SETUP ###

- Complete the Product Requirements Document (PRD) first
- Once complete, input the PRD into https://claude.ai/project/5cfd5869-171f-468d-bf73-df7c084e3cb0 to create a project plan. Use below prompt. 

> Create a project plan for the project described in the Product Requirements Document (PRD) provided. 

- The final Project Plan should be pasted into @project-plan-pp.md file

> PRODUCT REQUIREMENTS DOC (PRD) BELOW: 

> (INSERT)

> EXAMPLE PROJECT PLAN BELOW:

> (INSERT)

### INSTRUCTIONS FOR .CURSORRULES FILE SETUP ###

- Use https://chatgpt.com/g/g-ZoMOU3KbB-cursor-com-expert to create a .cursorrules file for the project
- Use the below prompt, including the example .cursorrules file provided as example
- The final .cursorrules file should be paseted into @.cursorrules file

> Create a .cursorrules file for the project described in the Product Requirements Document (PRD), using the below instructions and example .cursorrules file provided as example. IMPORTANT - The user has minimal development experience, so cursor should do all the development work possible - only if there are steps cursor cannot do shoud the user be asked to do something. And in that case, cursor should pause, instruct the user on what to do, and then resume the next step only when the user has completed the step. 

> PRODUCT REQUIREMENTS DOC (PRD) BELOW: 

> (INSERT)

> EXAMPLE .CURSORRULES FILE BELOW:

> (INSERT)

### INSTRUCTIONS FOR CREATING CURSOR NOTEBOOKS FOR PROJECT ###

Cursor notebooks are used as guidelines for cursor to automate specific types of development work, such updating the Project Log (pl.md) file, doing general development work, etc. We will improve this process in the future, but for now below are the cursor notebooks to be created at the start of a project. 

- Create a notebooked called "Project Log" with the below prompt: 
> Your task is to update the project log with the recent work that's been done and what needs to come next. Use the file  @projectlog-pl.md as a reference, Update it and make it detailed enough for a developer to know what you've done and what they would need to do next. Note that the AI developer that will be using the project log knows everything about how software development is done. So you do not need to provide any detail on the specifics of how something was done. You just need to be extremely clear on the what. Of what was done.  

- Create a notebook called "Development" with the below prompt: 
> Your task is to build the software project described in detail in the Product Requirements Document at @spec-prd-products-requirements-doc-prd.md, based on the sequential project plan at @projectlog-pl.md. Be sure to use the level of detail in your work as noted in  @.cursorrules. It's extremely important that you follow the rules that are in that file regarding how to work with the user as the user doesn't have experience in software development and it's important that you handle as much of the process as possible. 

- During your development work in cursor, you can guide cursor to these notebooks to do the task. For example, "@project log" will cause it to update the log with recent work that was done. 


