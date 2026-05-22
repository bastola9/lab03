# lab03
_lab of cep by nayan, alex and gabreal _

## Part B: System Design Challenge
### 4. Problem Analysis
Discuss what problems you encountered in Part A:
- Were changes overwritten or lost?
**No changes were overwritten. 3 versions of the poem were combined together**
- How did you decide which changes to keep?
**We discussed and agreed on which changes to keep. Final decision was to combine all 3 versions into 1**
- What if you had 5 people instead of 2?
**We would create different branches for each version and pull requests**
- How would you track who made which changes?
**We check the contributor's name based on the commit** 

## Part C: Document Your Solution
![alt text](<Poem version control.png>)

We had 2 issues.
One was communicational and another was a merging conflict: 
 - Nayan expressed his opinion about poem content, he made some changes to the final file and wrote a comment why he made changes to Alex version of it. (// the violet is violet not blue) 
- when Gabriel tried pushing the final file he got a merging conflict and had to resolve it. There was a conflict with Nayan version because both were pushing at same time to the same final file.

We communicated during the merging conflict and decided that we should combine all three poems. Gabreal resolved the conflict on his end and pushed the combined version with the changes.

### List the top 3 problems from Part A that your system solves
- Different versions of the same file and lack of communication
- Overwritten changes
- History of what have been done

#### - What was the most frustrating part of the collaboration chaos?
The most frustating problem was not understanding each other and trying to rewrite the same file  

#### - Which problem from Part A does your system design solve best?
The system successfully solved conflict of poem versions as we combined all 3 versions of it into the final file.

#### - What would happen if 10 people tried to collaborate this way?
if 10 people are working on a same file with no extra branches using , it's gonna be a total chaos without proper communication and a lots of conflicts between versions. 

#### - How does your design handle someone accidentally deleting the file?
We have centralized repo backup in the cloud and history of previous versions on github