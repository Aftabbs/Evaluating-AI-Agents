# Evaluating AI Agents

![image](https://github.com/user-attachments/assets/2ae1d2a6-f3ce-4cd5-b6d9-49005a03afbc)


This repository showcases our journey in developing a robust Data Analyst Agent, enhanced with routing, tracing, and comprehensive evaluation mechanisms. Our primary tools include [Arize AI's Phoenix](https://docs.arize.com/phoenix) and integrations with OpenTelemetry (OTel).

## Project Overview

1. **Data Analyst Agent Development**: We began by creating an AI agent capable of performing data analysis tasks, leveraging advanced machine learning models to interpret and process data effectively.

2. **Routing and Tracing Integration**: To manage and monitor the agent's operations, we incorporated routing mechanisms and implemented tracing using OpenTelemetry. This setup allows for detailed tracking of the agent's decision-making pathways and performance metrics.

3. **Trajectory Evaluation and Convergence Scoring**: Understanding the efficiency of the agent's problem-solving process is crucial. We introduced trajectory evaluation to assess the agent's reasoning paths and calculate convergence scores, which measure the consistency and optimality of the agent's actions over time. citeturn0search1

4. **Structured Evaluations and Monitoring**: Building upon the evaluation framework, we established structured methods to continuously assess and monitor the agent's performance, ensuring reliability and facilitating ongoing improvements.

## Key Components

- **Arize Phoenix Integration**: Phoenix serves as our AI observability platform, enabling effective experimentation, evaluation, and troubleshooting. It seamlessly integrates with OpenTelemetry, providing comprehensive tracing and evaluation capabilities. citeturn0search9

- **OpenTelemetry (OTel) Implementation**: We utilized OTel for standardized tracing across our AI systems. The `arize-otel` package offers a convenient setup for OpenTelemetry, streamlining the tracing process and ensuring compatibility with Phoenix. citeturn0search15

- **Convergence Score Calculation**: To quantify the agent's efficiency, we compute a convergence score. This metric evaluates whether the agent can respond to queries in an optimal number of steps, providing insights into its operational effectiveness. citeturn0search1




---

![image](https://github.com/user-attachments/assets/9b2fa4d2-f295-4d9e-b232-bd730e2adc8a)

![image](https://github.com/user-attachments/assets/fa21ed76-4a6e-46da-9b3f-6a48bdd333a3)

![image](https://github.com/user-attachments/assets/dae8f723-a20c-4ea1-8dd4-073e65fbc2da)

![image](https://github.com/user-attachments/assets/978024df-91e1-435e-a928-707f251cccf7)

![image](https://github.com/user-attachments/assets/10f7537f-a420-4b5d-8c5e-96b8300e4164)

![image](https://github.com/user-attachments/assets/7349db84-e029-4cd5-aaaf-604f3ec97453)

### AI Agent Structure
- Router (Segregates task's and tools  based on use cases)
- Skills (ex: RAG)
- Memory And State (Storing each response as a memory)

## Router

![image](https://github.com/user-attachments/assets/3e9baccf-bbfb-42ec-93f3-d3cc800e0d47)

## Skills

![image](https://github.com/user-attachments/assets/0dc0782a-cba2-4c88-96f4-660003302681)

## Memory and State

![image](https://github.com/user-attachments/assets/eed885ea-09c4-41ba-b8e7-586b0913a4ea)

## Example Agent Build (Data Analyst Agent)

![image](https://github.com/user-attachments/assets/a4acbb84-0cad-4ebd-8ba0-f49d1392655c)

## Tracing the Agent

![image](https://github.com/user-attachments/assets/8ebe3452-bfc2-45b7-801e-4b86fbe4ca6e)

## Adding Router and Skill Evaluations

![image](https://github.com/user-attachments/assets/3c0c63c8-a635-4bf3-ad99-6c4aa2a77433)

![image](https://github.com/user-attachments/assets/d6c30cce-7b41-42c2-8950-1e6a7803283b)

## Adding Trajectory Evaluations

![image](https://github.com/user-attachments/assets/6ecba2c5-d10c-4c80-944a-a8bbee9cbfcc)

![image](https://github.com/user-attachments/assets/f0439d33-d1c6-434c-8857-3af63034e12c)


## Adding Structure to Evaluations

![image](https://github.com/user-attachments/assets/a248c158-6bd5-4ca7-b096-144502552bde)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

