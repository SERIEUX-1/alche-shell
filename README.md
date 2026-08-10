# alche-shell

This repository contains Bash scripting exercises covering shell basics,
loops, conditions, parsing.

## Requirements

- All scripts are written for Ubuntu 20.04 LTS.
- Scripts pass Shellcheck (0.7.0) without errors.
- Scripts are executable (`chmod +x`).
- Each script starts with a shebang line, followed by a comment describing
  what it does (except where the task specifies an exact 2-line script).

## Directory: loops_conditions_and_parsing

| File | Description |
| --- | --- |
| `1-for_best_school` | Displays "Best School" 10 times using a `for` loop. |
| `2-while_best_school` | Displays "Best School" 10 times using a `while` loop. |
| `3-until_best_school` | Displays "Best School" 10 times using an `until` loop. |
| `4-if_9_say_hi` | Displays "Best School" 10 times, printing "Hi" after the 9th. |
| `5-4_bad_luck_8_is_your_chance` | Loops 1 to 10, printing "bad luck", "good luck", or "Best School" depending on iteration. |
| `6-superstitious_numbers` | Displays numbers 1 to 20, flagging superstitious numbers (4, 9, 17) with a `case` statement. |
| `7-clock` | Displays hours (0-12) and minutes (1-59) using nested `while` loops. |
| `8-for_ls` | Lists current directory contents, showing only the part of each name after the first dash. |
| `9-to_file_or_not_to_file` | Reports whether a file named `school` exists, is empty, and is a regular file. |
| `10-fizzbuzz` | Displays numbers 1 to 100 applying the FizzBuzz rule. |
| `11-read_and_cut` | Displays username, user ID, and home directory from `/etc/passwd`. |
| `12-tell_the_story_of_passwd` | Builds a narrative sentence per user from `/etc/passwd`. |
| `13-lets_parse_apache_logs` | Extracts visitor IP and HTTP status code from `apache-access.log` using `awk`. |
| `14-dig_the-data` | Groups Apache log entries by IP and status code, sorted by occurrence count. |
| `apache-access.log` | Sample Apache access log used by scripts 13 and 14. |
## Author
SERIEUX Elias
