# Investigating-with-Splunk

I uncovered several key details while investigating with Splunk on TryHackMe. I discovered that the adversary successfully created a backdoor user on one of the infected hosts and identified the registry key that was updated. I also determined the user the adversary was attempting to impersonate and found the command used to add the backdoor user from a remote computer. By analyzing the logs, I checked for any login attempts made by the backdoor user and identified the infected host where suspicious PowerShell commands were executed. Additionally, I determined the number of events logged for the malicious PowerShell execution and used CyberChef to decode the encoded PowerShell script, revealing the full URL involved in the attack.

## Task1-1
![Screenshot](Task1-1.png)

## Task1-2
![Screenshot](Task1-2.png)

## Task1-3
![Screenshot](Task1-3.png)

## Task1-4
![Screenshot](Task1-4.png)

## Task1-5
![Screenshot](Task1-5.png)

## Task1-6
![Screenshot](Task1-6.png)

## Task1-7
![Screenshot](Task1-7.png)

## Task1-8
![Screenshot](Task1-8png.png)

## Task1-9a
![Screenshot](Task1-9a.png)

## Task1-9b
![Screenshot](Task1-9b.png)

## Task1-9c
![Screenshot](Task1-9c.png)

## Task1-9d
![Screenshot](Task1-9d.png)

## Task1-9 Part-1 Correct Answer
![Screenshot](Task1-9Part1CorrectAnswer.png)

## Task1-9 Part-2 Correct Answer
![Screenshot](Task1-9Part2CorrectAnswer.pngg)

## All Task Completed
![Screenshot](AllTaskCompleted.png)
