# Analysis Overview
## Pycity Schools
The purpose of this analysis was to take a large amount of raw school and student data and manipulate it in order to make a presentation to the school board. We needed to determine overall school and student performance to see where improvements can be made. We started with just getting a summary of all the passing scores and passing percentages and how many schools we were dealing with. From there we could expand into how students performed based on things like: School Budget, Number of Attendees, School Type, etc. We also determined passing grade percentages for both math and reading in order to understand which school should be focusing on a specific subject more than the other. With all this information we can figure out the perfect budget for a school, the type of school that is best for learning, how many students should be in one school, and which subject needs the most focus.

## Pycity Challenge
The purpose of this analysis was to find the same data mentioned above after finding out one of the high schools had an integrity issue with their grades. We needed to remove the data for all of the 9th grade from Thomas High School and see how it effected the other values. With this new information we can come to a more accurate conclusion on school and student data.

# Results
The following results was made after removing the 9th grade from Thomas High School

* How is the district summary affected?: The district summary was almost identical we saw almost no drop in the average scores and passing percentage
* How is the school summary affected?: In the school summary we see that Thomas High School went from a 91% overall passing rate WITH the 9th grade to a 65% overall passing rate WITH OUT the 9th grade
* How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?: Thomas High School went from 2nd best school in the district to the 8th best school in the district
* How does replacing the ninth-grade scores affect the following:
  1. Math and reading scores by grade: Very small change as the only value affected is the 9th grade of THS which is set to NAN or 0
  2. Scores by school spending: Thomas High School still has a spending of $630 - $644 which dropped this category on all 3 percentages by about 7% each
  3. Scores by school size: Thomas High School went from 1635 to 1174 in school size which ended up dropping all 3 of their percentages for medium sized schools by about 5%
  4. Scores by school type: Thomas High School was a charter school which dropped all 3 percentages for charter schools by about 4% each
 
# Summary
In conclusion we can see that after removing the 9th grade Thomas High School dropped from 2nd on the district list to 8th. Their overall passing percentage went from a 91% to 65%. Their spending per student dropped around $200. Finally their total student count dropped from 1635 students to 1174. 
