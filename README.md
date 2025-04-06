# Agentic-Rag---Plan-and-Execute-Agent

𝗔𝗴𝗲𝗻𝘁𝗶𝗰 𝗥𝗔𝗚 
(𝗗𝗼𝗰𝘂𝗺𝗲𝗻𝘁𝘀 + 𝗗𝗲𝗲𝗽𝗟𝗮𝗸𝗲 + 𝗥𝗔𝗚 + 𝗧𝗼𝗼𝗹 + 𝗔𝗴𝗲𝗻𝘁)

Sharing my latest project, 𝗔𝗴𝗲𝗻𝘁𝗶𝗰 𝗥𝗔𝗚, which leverages the innovative Plan and Execute strategy inspired by the BabyAGI framework. This approach is designed to enable complex, long-term planning through frequent interactions with language models, The reason for this integration is to 𝗲𝗻𝗵𝗮𝗻𝗰𝗲 𝘂𝘀𝗲𝗿 𝗲𝘅𝗽𝗲𝗿𝗶𝗲𝗻𝗰𝗲 𝗮𝗻𝗱 𝗳𝗮𝗰𝗶𝗹𝗶𝘁𝗮𝘁𝗲 𝗳𝗮𝘀𝘁𝗲𝗿, 𝗺𝗼𝗿𝗲 𝗲𝗳𝗳𝗶𝗰𝗶𝗲𝗻𝘁 𝗱𝗲𝗰𝗶𝘀𝗶𝗼𝗻-𝗺𝗮𝗸𝗶𝗻𝗴

𝗣𝗹𝗮𝗻 𝗮𝗻𝗱 𝗘𝘅𝗲𝗰𝘂𝘁𝗲 𝗢𝘃𝗲𝗿𝘃𝗶𝗲𝘄

The Plan and Execute strategy is a two-pronged approach:
𝗣𝗹𝗮𝗻: Utilizes the language model's capabilities to devise steps for a plan, adeptly handling ambiguities and unusual scenarios.

𝗘𝘅𝗲𝗰𝘂𝘁𝗲: Interprets the planner's goals or steps and identifies the necessary tools/actions to execute each step effectively.

Workflow
Here's a detailed look at the workflow that powers Agentic RAG:

𝟭. 𝗦𝗮𝘃𝗶𝗻𝗴 𝗗𝗼𝗰𝘂𝗺𝗲𝗻𝘁𝘀 𝗶𝗻 𝗗𝗲𝗲𝗽 𝗟𝗮𝗸𝗲:
We begin by collecting and processing the latest AI news articles, storing them in Deep Lake. This repository acts as a comprehensive database for our agents, ensuring they have access to a wealth of information.

𝟮. 𝗗𝗲𝘃𝗲𝗹𝗼𝗽𝗶𝗻𝗴 𝗮 𝗗𝗼𝗰𝘂𝗺𝗲𝗻𝘁 𝗥𝗲𝘁𝗿𝗶𝗲𝘃𝗮𝗹 𝗧𝗼𝗼𝗹:
A specialized tool is crafted to extract the most relevant documents from Deep Lake based on specific queries. This ensures that our agents can quickly access the information they need to address complex questions.

𝟯. 𝗜𝗺𝗽𝗹𝗲𝗺𝗲𝗻𝘁𝗶𝗻𝗴 𝘁𝗵𝗲 𝗣𝗹𝗮𝗻 𝗮𝗻𝗱 𝗘𝘅𝗲𝗰𝘂𝘁𝗲 𝗔𝗴𝗲𝗻𝘁:
The core of the project is the 𝗣𝗹𝗮𝗻 𝗮𝗻𝗱 𝗘𝘅𝗲𝗰𝘂𝘁𝗲 𝗮𝗴𝗲𝗻𝘁, which formulates strategies to address queries, such as creating topic overviews. By leveraging OpenAI’s model and LangChain’s framework, the agent dynamically retrieves and processes information to generate insightful summaries.

𝗔𝗽𝗽𝗹𝗶𝗰𝗮𝘁𝗶𝗼𝗻𝘀
This framework is versatile and can be adapted across various domains, providing a scalable solution for diverse analytical needs
