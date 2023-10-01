# RequestSPY
<p>A Python based non GUI tool built using the concepts of Prompt Engineering to check the requests recieved at server side and verifies wether the request is trying to exploit any vulnerability.</p>
<p>The currrent version of tool in this repo works for apache2 and enginx servers on linux.</p>
<b>Tools and skills: Python, Prompt  Engineering, servers, log files, OS, vulnerable requests, Pentesting, CyberSecurity.</b>

# Instalation steps:
> Create a folder named RequestSPY.
> Open terminal in that folder/ access that folder via terminal.
> Type command <i>git clone https://github.com/kreet1010/RequestSPY.git</i>.
> Access the python file holding the name of server that you are using and find a variable named openai_API and feed your api key value as a string to that variable.
> To understand the process to generate openai API key <a href="https://www.geeksforgeeks.org/openai-python-api/">click here</a>

# User guide:
> Remember to start the virtual environment using the command <i>source ./bin/activate</i>
> Determine the server being used in your device and run the respective python file.
> The respective responses based on the requests stored in the log files will be recorded and stored in the ReqCheck{date of scan in %d-%m-%y format}.json file in the ReportsJSON folder.
> This tool uses free API of openai that allows only 3 requests per minute. A paid API version would drastically speedup the software.

# Troubleshooting guide.
> Check if you've correctly started the virtual env using the <i>source ./bin/activate</i> command. Try Restarting the virtual environment.
> Try Restarting the server again. <i>sudo systemctl restart apache2</i>/<i>sudo systemctl restart nginx</i>
> Try downloading the dependancies again.
<i>pip install openai</i>
<i>pip install requests</i>
> If issue persists, please contact me on <a href="www.linkedin.com/in/kreet-rout-a404121ba">linkedin</a>
