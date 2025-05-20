# Rapport-Robot-II
<p align="justify">
This repository contains dialogue samples from our dialogue robots to enhance the clarity of our paper titled "Rapport-Building Dialogue Strategies for Deeper Connection: Integrating Proactive Behavior, Personalization, and Aizuchi Backchannels," which has been submitted to INTERSPEECH 2025.
</p>

## Dialogue Samples
<div style="text-align: justify;">
  <p>
    Our study examines four dialogue robots designed to foster rapport through small talk over 28 turns centered on travel destinations. The robots are as follows:
  </p>

  <ol>
    <li><strong>CSFS4o:</strong> Uses the CO-STAR and few-shot framework with GPT-4o to elicit rapport-building dialogue strategy (RBDS), focusing on proactive engagement, personalization, and increased use of Aizuchi backchannels.</li>
    <li><strong>CSFS35:</strong> Implements the same frameworks as CSFS4o but with GPT-3.5 Turbo. Comparing CSFS4o and CSFS35 allows us to evaluate the impact of model differences.</li>
    <li><strong>ORG35:</strong> Applies the original RBDS built by Baihaqi et al. [3] with GPT-3.5 Turbo, without specific strategies for proactive engagement, personalization, or Aizuchi backchannels, allowing us to evaluate whether the addition of these behaviors enhances rapport.</li>
    <li><strong>ORG4o:</strong> Applies the original RBDS with GPT-4o, enabling the assessment of whether improvements in dialogue quality stem from the LLM's enhanced capabilities or the inclusion of proactive engagement, personalization, and backchannels.</li>
  </ol>
</div>

<p align="justify">
[3] M. Y. Baihaqi, A. Garcia Contreras, S. Kawano, and K. Yoshino, “Rapport-driven virtual agent: Rapport building dialogue strategy for improving user experience at first meeting,” in Interspeech 2024, 2024, pp. 4059–4063.
</p>

### CSFS4o
<p align="center">
  <img src="https://github.com/user-attachments/assets/7fd8a26c-9df8-4dad-b703-59a90007c9db" alt="CommA">
</p>
<p align="justify">
CSFS4o demonstrates a robust ability to establish rapport by integrating proactive engagement,
personalization, and frequent aizuchi responses into rapport building dialogue strategy (RBDS).
It effectively uses RBDS tailored to the participant’s interests, such as Japanese players in
Major League Baseball. CSFS4o proactively explores the user's preferences by asking
personalized questions, like recommending a team to watch and inquiring about favorite
players. Additionally, it shares a very specific story about a friend who watched the participant's
favorite player, creating a personal connection. These behaviors make the conversation flow
more naturally, easier to follow, align closely with the user’s interests, and ultimately foster a
higher level of rapport.
</p>

### CSFS35
<p align="center">
  <img src="https://github.com/user-attachments/assets/c1e712b7-e1e8-44bd-a308-ea76d477bfca" alt="CommI">
</p>
<p align="justify">
CSFS35 incorporates aizuchi and proactive behavior, demonstrating the utilization of RBDS and
follow-up questions. While it effectively sustains the conversation by introducing new topics,
such as sightseeing in New York, its limitations become evident. The reliance on GPT-3.5 Turbo
hinders its ability to fully understand context and limits its capacity to provide in-depth responses
or specific information, due to the model's restricted knowledge. As a result, CSFS35 remains
proactive and uses aizuchi but lacks the level of deep personalization seen in CSFS4o.
</p>

### ORG4o
<p align="center">
  <img src="https://github.com/user-attachments/assets/7b31db34-0ef4-4b93-a2f2-13d28c25d81a" alt="CommO">
</p>
<p align="justify">
ORG4o leverages the original RBDS with the strengths of GPT-4o, offering thoughtful and
creative responses. It employs a rapport-building dialogue strategy with specific details, such as
Yankee Stadium, and highlights unique aspects of New York, like its culinary offerings and
cinematic charm. However, it falls short of being as personally engaging as CSFS4o, primarily
due to its lack of proactive exploration of the user’s interests. For example, while ORG4o shares
a story about a friend, it does not delve into the same level of personalized detail seen in
CSFS4o. Additionally, ORG4o uses minimal aizuchi, which affects its ability to maintain a fluid
conversation.
</p>

### ORG35
<p align="center">
  <img src="https://github.com/user-attachments/assets/3e929137-1a73-4f1e-a4a9-472bbd2d61c8" alt="CommE">
</p>
<p align="justify">
ORG35 serves as the baseline, reflecting the limitations of the original RBDS with GPT-3.5
Turbo. While its responses are conversational, they lack personalization and proactivity,
resulting in a more generic interaction. ORG35 focuses mainly on delivering factual or
encouraging statements, without exploring the participant's interests or delving into the specifics
of the destination. This approach creates a functional, yet less engaging, conversational
experience.
</p>
