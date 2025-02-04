# rat_claude
input -> deepseek_history(user) -> deepseek_reasoner -> reasoning -> [input, reasoning] -> claude/openai -> response 
response -> deepseek_history(assistant)

# rat
input -> deepseek_history(user) -> deepseek_reasoner -> reasoning -> prompt(input, reasoning) -> router_history(user)-> openrouter -> response
response -> deepseek_history(assistant)
response -> router_history(assistant)
