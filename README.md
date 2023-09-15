# Intro

AI hallucination refers to when an AI model “starts to make up stuff — stuff that is not in-line with reality,”, an issue that has increasingly vexed the realm of artificial intelligence. AI hallucinations can lead to incorrect predictions or suggestions, potentially causing unwanted ramifications. Addressing these issues is not just a matter of technical refinement, but a critical obligation to ensure the trust and reliability of AI systems in real-world situations.

However, truth is a complex, nebulous concept with varying interpretations across different enterprises and groups, contributing to the intricacies of solving this issue. Objective truth is concrete, based on factual data, while subjective truth may differ based on group perspectives inherent in their operating environments. This variability poses a significant challenge in building an AI model that aligns with the individual 'truths' of diverse groups. As such, a successful project must incorporate a multifaceted approach that recognizes these differences, ensuring AI models remain robust, flexible, and reliable, regardless of the contextual setting. This framework will enable the creation of AI systems that are tailored for each organization's unique 'truth,' reducing the likelihood of AI hallucination and fostering a more accurate, efficient AI ecosystem.

This problem was observed across our project, Zapdroid which is an AI chatbot designed for businesses to save time.

# Approach

Our approach is to develop a filter layer that meticulously applies to each AI-generated output. This filter layer is linked to a side vector database encompassing comprehensive organizational information. Every factual output produced by the AI is scrutinized against this vector database, serving as a verification checkpoint. This process ensures that each output aligns with the organization's source of truth, promising consistency and reducing the instances of AI hallucination.


