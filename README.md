# About the Alameda Health System Empanelment Project

During the summer of 2022, I interned for the Business Intelligence department at Highland Hospital in Oakland, a branch of the alameda health system. 
While there, the main project I worked on was focused on processing empanelment data. Empanelment is the process of assigning patients to individual 
primary care providers (PCP’s) and care teams based on possible patient sensitivities and existing family preferences. Empanelment is the basis for 
population health management, and its purpose is to ensure that every established patient receives the best care possible, regardless of the frequency 
of their visits or where they and their PCP are assigned. Accepting responsibility for a finite number of patients, instead of the universe of patients 
seeking care in the practice, allows the provider and care team to focus more directly on the needs of each patient. The data I worked with in this 
project  is used to keep track of empanelment processes and show the most up to date (by month) assignment numbers of each PCP, separated by branch and
level at their location. The final product for the  processing and visualizing of this empanelment data was made of two main components. First, SQL code
that read PCP and patient data from a massive database, then ordered and processed it into groups by the PCP's level and the specific branch at which they
were located. After this, the data was imported into Microsoft Power BI, which constructed interactive, auto-responding visuals that replaced the old 
system of a single excel sheet that hand to be updated manually each month. While these Power BI dashboards made it much easier to interact with the data, 
the new system behind them also allowed the visuals to respond automatically to any changes in the PCP data. If a PCP's name's changed, the program would 
detect that and prevent the creation of duplicate names, if a PCP's level at a hospital shifted the program would notice that and respond accordingly and 
if a PCP died, retired or left AHS, their name would be removed from the system and the dashboard data would be automatically adjusted.

While I have not included the full code and Power Bi files that I helped create and worked on at AHS's request, I have included some screenshots of the 
dashboards I created and some of the DAX measures I wrote to process and produce the final numbers used.
