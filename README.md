# Rapport-Robot-II
<p align="justify">
This repository contains dialogue samples from our dialogue robots to enhance the clarity of our paper titled "Rapport-Building Dialogue Strategies for Deeper Connection: Integrating Proactive Behavior, Personalization, and Aizuchi Backchannels," which has been submitted to INTERSPEECH 2025.
</p>

## Dialogue Samples
<p align="justify">
This repository contains dialogue samples from our dialogue robots to enhance the clarity of our paper titled "Rapport-Building Dialogue Strategies for Deeper Connection: Integrating Proactive Behavior, Personalization, and Aizuchi Backchannels," which has been submitted to INTERSPEECH 2025. We will move the data to GitHub upon acceptance.

Our study examines four dialogue robots designed to foster rapport through small talk over 28 turns centered on travel destinations. The robots are as follows:  

1. CSFS4o: Uses the CO-STAR and few-shot framework with GPT-4o to elicit rapport building dialogue strategy (RBDS), focusing on proactive engagement, personalization, and increased use of Aizuchi backchannels. 

2. CSFS35: Implements the same frameworks as CSFS4o but with GPT-3.5 Turbo. Comparing CSFS4o and CSFS35 allows us to evaluate the impact of model differences.

3. ORG35: Applies the original RBDS built by Baihaqi et al. [3] with GPT-3.5 Turbo, without specific strategies for proactive engagement, personalization, or Aizuchi backchannels, allowing us to evaluate whether the addition of these behaviors enhances rapport.

4. ORG4o: Applies the original RBDS with GPT-4o, enabling the assessment of whether improvements in dialogue quality stem from the LLM's enhanced capabilities or the inclusion of proactive engagement, personalization, and backchannels.
</p>

<p align="justify">
[3] M. Y. Baihaqi, A. Garcia Contreras, S. Kawano, and K. Yoshino, “Rapport-driven virtual agent: Rapport building dialogue strategy for improving user experience at first meeting,” in Interspeech 2024, 2024, pp. 4059–4063
</p>

### CommA 
<p align="center">
  <img src="https://github.com/user-attachments/assets/0ff6a9c3-33e2-4944-a88a-b854cf789b61" alt="CommA">
</p>
<p align="justify">
CommA demonstrates a robust ability to establish rapport by integrating proactive engagement, personalization, and frequent aizuchi responses. It effectively uses a rapport-building dialogue strategy tailored to the participant’s interests, such as Japanese players in Major League Baseball. CommA proactively explores the user's preferences by asking personalized questions, like recommending a team to watch and inquiring about favorite players. Additionally, it shares a very specific story about a friend who watched the participant's favorite player, creating a personal connection. These behaviors make the conversation flow more naturally, easier to follow, align closely with the user’s interests, and ultimately foster a higher level of rapport.
</p>

### CommO
<p align="center">
  <img src="https://github.com/user-attachments/assets/9907ac48-cafc-4c1a-a6d9-60b6b2854820" alt="CommI">
</p>
<p align="justify">
CommO incorporates aizuchi and proactive behavior, demonstrating the utilization of rapport-building strategy and follow-up questions. While it effectively sustains the conversation by introducing new topics, such as sightseeing in New York, its limitations become evident. The reliance on GPT-3.5 Turbo hinders its ability to fully understand context and limits its capacity to provide in-depth responses or specific information, due to the model's restricted knowledge. As a result, CommO remains proactive and uses aizuchi but lacks the level of deep personalization seen in CommA.
</p>

### CommI
<p align="center">
  <img src="https://github.com/user-attachments/assets/0a69e032-7efc-4646-9bb6-fce61847a424" alt="CommO">
</p>
<p align="justify">
CommI leverages the strengths of GPT-4o, offering thoughtful and creative responses. It employs a rapport-building dialogue strategy with specific details, such as Yankee Stadium, and highlights unique aspects of New York, like its culinary offerings and cinematic charm. However, it falls short of being as personally engaging as CommA, primarily due to its lack of proactive exploration of the user’s interests. For example, while CommI shares a story about a friend, it does not delve into the same level of personalized detail seen in CommA. Additionally, CommI uses minimal aizuchi, which affects its ability to maintain a fluid conversation.
</p>

### CommE
<p align="center">
  <img src="https://github.com/user-attachments/assets/67c43f6c-2ae0-49ce-b272-9ad6a07a6edd" alt="CommE">
</p>
<p align="justify">
CommE serves as the baseline, reflecting the limitations of the older prompt with GPT-3.5 Turbo. While its responses are conversational, they lack the personalization and proactivity, resulting in a more generic interaction. CommE focuses mainly on delivering factual or encouraging statements, without exploring the participant's interests or delving into the specifics of the destination. This approach creates a functional, yet less engaging, conversational experience.
</p>
