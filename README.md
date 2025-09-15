peak-lost-and-found

A police station’s lost-and-found agent.

Overview

This project is a simulation of a police station’s lost-and-found agent. The station maintains a collection of lost wallets. The process is simple and effective: the agent uses a person’s face ID along with their ID.

If the face and ID match an entry in the lost wallets database, the agent returns the wallet.

If they do not match, the claim is denied, and no wallet is released.

Features

Agent-based design: Goes beyond a simple chatbot by incorporating decision-making logic.

PyTorch-powered: Uses deep learning models for natural language understanding and response generation.

String matching & processing: Powered by RapidFuzz and regex for flexible input handling.

Interactive interface: Built with Gradio for real-time interaction in Colab.

Colab-optimized: Supports GPU acceleration for faster training and inference.

Project Structure

Data Preparation → Loads and preprocesses datasets (CSV/Excel supported).

Model Training → Defines and trains the agent’s model using PyTorch.

Agent Logic → Implements reasoning and decision-making layers.

Interface → Deploys the trained agent with Gradio for user interaction.

Requirements

The notebook will automatically install the required dependencies:

pip install openpyxl rapidfuzz torch gradio

Usage

Open the notebook in Google Colab.

Enable GPU: Runtime > Change runtime type > GPU (T4/L4 recommended).

Run all cells to:

Install dependencies

Load and preprocess data

Train the agent

Launch the interface

The final cell will provide a Gradio link where you can interact with the agent.

Future Improvements

Extend the agent’s reasoning capabilities.

Add multi-agent collaboration features.

Integrate external APIs for broader functionality.

Enhance memory for contextual, multi-turn interactions.

Peak Members

Razan Takruri — Leader

Renad Naser

Obada Hamdan
