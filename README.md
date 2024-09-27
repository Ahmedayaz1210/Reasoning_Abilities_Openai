# Reasoning_Abilities_Openai

This project implements an autonomous agent with advanced reasoning capabilities, incorporating a planner, reasoner, executor, and evaluator, all equipped with short-term and long-term memory.

## Project Overview

The Reasoning_Abilities_Openai project aims to create an intelligent agent capable of breaking down complex queries into subtasks, reasoning about how to complete each subtask, executing the necessary actions, and evaluating the results. This agent leverages OpenAI's language models to perform these cognitive functions.

## Components

1. **Planner**: Breaks down user queries into a list of subtasks.
2. **Reasoner**: Provides reasoning on how to execute each subtask.
3. **Actioner**: Determines the most appropriate action to take for each subtask.
4. **Executor**: Carries out the decided action, which can be either generating and executing code or providing reasoning.
5. **Evaluator**: Assesses the results of each subtask and determines if a retry is necessary.
6. **Final Answer Extractor**: Synthesizes the results from all subtasks to provide a final answer to the user's query.
