# VoiceVista

## Objective 

Indicating a comprehensive view (vista) into customer calls through voice analysis and tone-based live call analysis.

## Problems:
- The system mush accurately identify the context and tone of customer query during live calls.
- The System must provide real-time recommendations to the support team during the call without significant delays.
- Ensure the solution is fully deployed on Azure Cloud, leveraging its scalability and security features for handling sensitive customer data and high-traffic volumes.
- Adhere to all relevant data protection and privacy regulations, ensuring customer data is securely processed and stored.

## Key features:
- Real time audio processing and analysis is enabled
- Tone and sentiment detection is enabled

## Implementation:
- Implement Speech to Text to transcribe live audio calls.
- Use Text Analytics to analyze the sentiment and extract key phrases from the transcribed text.

## Tools used


# library installed 
```commandline
pip install azure-cognitiveservices-speech
```