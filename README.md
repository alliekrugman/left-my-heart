**Organ donation needs a bigger heart **


*What I aimed to accomplish*: This project explores inequity in organ donation in the U.S. with data from the Organ Procurement and Transplantation Network (OPTN).

*Findings*: By cleaning, joining and visualizing multiple datasets, I found that Black Americans continue to have the longest median waiting time for organ transplants. I also found that waitlists of organ candidates grow longer every year, and thousands continue to die preventable deaths. During the early months of COVID, waitlist additions and removals both dropped.

*Data collection*: The three main datasets I used are:
  - addition.csv: # of people added to donation waitlists each year
  - removal.csv: # of people removed from donation waitlists each year
  - Median_waiting_time_heart.csv: Median waiting time by ethnicity

The OPTN had an <a href="https://optn.transplant.hrsa.gov/data/view-data-reports/national-data/">easy-to-use database</href> with tons of information.

*Data analysis*: I had to clean each dataset using a combination of Excel and Python. In the removal dataset, I deleted other possible reasons for waitlist removal that were less significant for my line graph, including transfer to another hospital, too sick to transplant, and condition improved. Instead, I focused on deaths waiting and transplants (I added live donor transplants and deceased transplants together). For addition and median waiting time, I deleted columns listing total numbers and other unnecessary information. Once my datasets were cleaned, I joined addition and removal in Python. I then visualized the output and waiting time datasets as graphs in DataWrapper.

*What I wanted to do*: I struggled the most with coming up with a direction and interesting angle. There is a wealth of data on organ donation (thanks OPTN!) and I explored almost all of it. Originally, I was going to focus on states that had recently adopted an opt-out policy, but it became clear not enough time had passed for there to be an interesting difference before and after the policy. I then thought about mapping all the centers in the U.S. and their organ donation need, but that was so clearly correlated with population. California has by far the most donors and the most need, but when divided by population they're 10th or so on the list. In this version of the project, I had removed everyone under 18, as children require parental consent to opt-out of donation. It was way too complicated.

*Skills and struggles*: This project was really helpful in applying the approaches we'd learned in class to an a real-life issue. However, I often resorted to quickly deleting a column in excel rather than manipulating datasets in Python, which hopefully I'll become more comfortable with as the course goes on.

I also learned that I love the process of creating visualizations and designing a webpage in HTML/CSS! (even though this one I lifted almost completely from a previous student) I look forward to learning AI to HTML and making more creative projects.
