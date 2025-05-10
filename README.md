# Azure-Foundry-AI-development-project
In this MSFT exercise, I use Azure AI Foundry portal to create a hub and project, ready for a team of developers to build an AI solution.
## Create a hub and project
<img width="996" alt="image" src="https://github.com/user-attachments/assets/988b59e7-b528-40f4-8f58-819e285861f1" />
View the resource group in the Azure portal to see the Azure resources that have been created to support your hub and project.
<img width="1234" alt="image" src="https://github.com/user-attachments/assets/9d4f04ad-5a21-496c-8e78-4fb255708ca1" />
## Create and Add a connected resource
Create a new Azure AI Services resource
<img width="961" alt="image" src="https://github.com/user-attachments/assets/aa1c9731-9c60-4985-a9f4-bdc49d120e39" />
In the Text translation page, in the Try it out section, view the Try with your own tab.
Select either of your Azure AI Services resources and then try translating some text (for example, Hello world) from one language to another.
<img width="1177" alt="image" src="https://github.com/user-attachments/assets/19654a0f-876e-4595-87d4-f63f44f68ce2" />
## Compare Models - compare the metrics for these models visually using
Accuracy
Coherence
Fluency
Relevance
<img width="1615" alt="image" src="https://github.com/user-attachments/assets/e8d9c5c4-fac4-4fa5-aa40-ac03a530f056" />
Compare Models in Chat playground
Prompt 1: "I have a fox, a chicken, and a bag of grain that I need to take over a river in a boat. I can only take one thing at a time. If I leave the chicken and the grain unattended, the chicken will eat the grain. If I leave the fox and the chicken unattended, the fox will eat the chicken. How can I get all three things across the river without anything being eaten?"
Promp 2: "Explain your reasoning"
Chat with the gpt-4o model
Response 1: This is a classic river crossing puzzle! Here's how you can get all three items across the river safely:
Take the chicken across the river first and leave it on the other side.
Go back to the starting side alone.
Take the fox across the river and leave it on the other side, but take the chicken back with you to the starting side.
Take the bag of grain across the river and leave it with the fox on the other side.
Go back to the starting side alone.
Take the chicken across the river one final time.
Now all three (the fox, the chicken, and the bag of grain) are on the other side of the river, and nothing has been eaten!
Response 2: Certainly! Let’s break down the reasoning step by step:

The puzzle has two constraints:
The fox will eat the chicken if left unattended together.
The chicken will eat the grain if left unattended together.

The goal is to get all three across the river safely, but you can only transport one item at a time in the boat. This means you’ll need to carefully plan your trips to ensure no dangerous combinations are left unattended on either side of the river.
 
Step-by-Step Explanation
 
Take the chicken across the river first.
The chicken is safe on the far side because it’s alone.
The fox and the grain are left on the starting side, which is fine because they don’t interact with each other.
 
2. Go back to the starting side alone.
Now you’re back on the starting side, leaving the chicken safely on the far side.
 
3. Take the fox across the river.
Leave the fox on the far side, but take the chicken back with you to the starting side.
This ensures that the fox and chicken are not left unattended together (the fox would eat the chicken).
 
4. Take the bag of grain across the river.
Leave the grain on the far side with the fox. This is safe because the fox doesn’t eat grain.
The chicken is still with you on the starting side.
 
5. Go back to the starting side alone.
Now you’re back on the starting side, leaving the fox and the grain safely on the far side.
 
6. Take the chicken across the river one final time.
Now all three (the fox, the chicken, and the grain) are on the far side of the river.
No dangerous combinations were left unattended at any point.
 
Why This Works
This plan works because it avoids leaving the fox and chicken together (where the fox would eat the chicken) and avoids leaving the chicken and grain together (where the chicken would eat the grain). By carefully transporting items and sometimes bringing one back, you ensure that the constraints are never violated.

This solution relies on "backtracking," which means taking an item back to the starting side temporarily to rearrange the situation and avoid conflicts.

Phi-3.5-mini-instruct - version:6
Response 1: To solve this problem, you need to follow these steps, ensuring that the chicken and the grain are never left together without your supervision, and the fox and the chicken are never left together without your supervision:
First, take the chicken across the river, leaving the fox and the grain on the original side. This ensures that neither the chicken nor the grain will be eaten while you're away.
Next, return alone to the original side and take the fox across the river. Do not leave the fox with the chicken, as the fox would eat the chicken.
Leave the fox on the other side of the river and take the chicken back with you to the original side. This ensures that the chicken does not eat the grain while you're away.
Leave the chicken on the original side and take the bag of grain across the river. Now, the grain is safe on the other side, but the chicken and the fox are still on different sides.
Finally, return alone to the original side one last time and take the chicken across the river. This ensures that all three items - the fox, the chicken, and the grain - are safely on the other side of the river without any being eaten.
By following these steps, you can successfully transport the fox, the chicken, and the bag of grain across the river without anything being eaten.
Response 2: Certainly! The reasoning behind the steps I provided is based on the constraints given in the problem and the goal of safely transporting all three items across the river without any being eaten. Here's a detailed breakdown of the logical process:
Initial Move (Step 1): Take the chicken across first. This is the most vulnerable item, as it can be eaten by the fox. By taking the chicken first, we ensure that it's not left with the fox or the grain, which could lead to it being eaten. This step also allows us to make use of the boat's capacity to carry only one item at a time.
Return (Step 2): After safely transporting the chicken, we need to return to the original side to get the fox. This is necessary because if we left the chicken with the grain, the chicken would eat the grain. By returning alone, we prevent this situation and bring the fox over to the side with the chicken.
Switch (Step 3): Now, we leave the fox on the new side (with the chicken) and take the chicken back to the original side. This step is crucial because it ensures that the chicken is never left with the grain alone. We can't leave the fox with the grain, as the fox would eat the chicken, but we can't leave the chicken with the grain either. This move creates a safe separation between the fox and the grain.
Transfer Grain (Step 4): With the chicken back on the original side, we now take the bag of grain across the river. This leaves the fox on the new side with the chicken and the grain, ensuring that no one is left in a vulnerable position. The fox cannot eat the grain, and the chicken cannot eat the fox, so this move is safe.
Final Return (Step 5): The last step is to return alone to the original side one last time to get the chicken. By doing this, we ensure that all three items (the fox, the chicken, and the grain) are safely across the river. We've successfully avoided any scenarios where one item would eat another, adhering to the constraints of the problem.

Throughout these steps, the key principle is to never leave the chicken and the grain or the fox and the chicken unattended together. By carefully planning each trip and return, we can ensure that all items are transported safely without any being eaten. This solution is based on the process of elimination and careful consideration of the constraints and the relationships between the items.


## Conclusion
I prefer gpt 4o because it formats it's response in bullets and it is easier for someone with a logical mind to understand and read. On the contrary, the Phi 3.5 was a great description but it's not clear to read, its busy.













