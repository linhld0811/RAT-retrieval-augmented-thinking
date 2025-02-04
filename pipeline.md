# rat_claude
input -> deepseek_history(user) -> deepseek_reasoner -> reasoning -> [input, reasoning] -> claude/openai -> response 
response -> deepseek_history(assistant) <br>

# rat
input -> deepseek_history(user) -> deepseek_reasoner -> reasoning -> prompt(input, reasoning) -> router_history(user)-> openrouter -> response <br>
response -> deepseek_history(assistant) <br>
response -> router_history(assistant) <br>
