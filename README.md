# Minishell

Welcome to Minishell, a simplified shell program inspired by bash. This project focuses on heavy parsing, expansion, environment variables, pipes, redirections, heredoc, double quotes, and single quotes.

# Features:

• Basic command execution <br />
• Parsing and tokenization of user input <br />
• Environment variable expansion <br />
• Handling single and double quotes <br />
• Input and output redirection <br />
• Command pipelines (| symbol) <br />
• Heredoc functionality <br />

Check the subject for more details!

# Usage: <br />

1. Clone the repository to your local machine:
```
git clone https://github.com/eetukoljonen/minishell.git
```
2. Build the program:
```
make
```
3. Start the program
```
./minishell
```


# Examples:

1. Basic command execution: ls, echo Hello, pwd
2. Variable expansion: echo "Hello, $USER"
3. Input and output redirection: cat < input.txt > output.txt
4. Command pipelines: ls | grep ".txt"
5. Heredoc functionality: <br />
cat << EOF <br />
Line 1 <br />
Line 2 <br />
EOF <br />

![minishell](https://github.com/eetukoljonen/minishell/assets/120648288/18404dec-f123-49c7-874e-cba5a1c675e5)

