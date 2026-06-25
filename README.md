# Evolving-Machine
A Machine that changes itself and evolves over time.

In order to launch it from the command line or as a Python subprocess:
```bash
echo "Theodotos-Alexandreus: Change your behavior, machine." \
  | uvx evolving-machine \
    --provider-api-key sk-proj-... \
    --github-token ghp_... 
```

Or, with a local pip installation:
```bash
pip install evolving-machine
```
Set the environment variables:
```bash
export PROVIDER_API_KEY="sk-proj-..."
export GITHUB_TOKEN="ghp_..."
```
Then:
```bash
evolving-machine -a multilogue.txt
```
Or:
```bash
evolving-machine multilogue.txt > response.txt
```
Or:
```bash
evolving-machine -a multilogue.txt > tmp && echo tmp > multilogue.txt
```

Or use it in your Python code:
```Python
# Python
import evolving_machine
```
