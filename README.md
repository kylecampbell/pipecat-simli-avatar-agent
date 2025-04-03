# Pipecat Simli AI Avatar Agent

This is an example of a Simli avatar that uses the Pipecat SDK to create an AI agent that can be used in a Daily room.

## Installation

```console
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Setup

In this project's directory, run the following command to copy the `.env.example` file to `.env`:

```console
cp .env.example .env
```

Edit the `.env` file with your own values.

### Simli

Visit https://simli.com to get your `SIMLI_API_KEY` and `SIMLI_FACE_ID`.

### OpenAI

Visit https://platform.openai.com to get your `OPENAI_API_KEY`.

### ElevenLabs

Visit https://elevenlabs.io to get your `ELEVEN_API_KEY` and `ELEVEN_VOICE_ID`.

### Daily

Visit https://daily.co to get your `DAILY_API_KEY`.
In the Daily dashboard, create a room and copy the `URL` of the room to use as `DAILY_SAMPLE_ROOM_URL`.
It should look something like this: `https://YOURDOMAIN.daily.co/YOURROOM`.

## Usage

In your browser, navigate to the room URL you created in the Daily dashboard and join the room.
Then, run the following command to start the agent:

```console
python simli_agent.py
```
