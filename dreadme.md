Which of the following factors are NOT advantages of automation?
Increasing the number of jobs


Which variable contains the number of arguments passed to the script?
$#


Which symbol is used to execute a command in the background?
&


What does the && operator mean on the command line?
Executes the second command only if the first one completed successfully


How to get all elements of an array in Bash?
${array[@]}


What is the difference between while and until loops?
while executes while the condition is true, until – while the condition is false


Which operator checks that a file exists and is a regular file?
-f


What are environment variables?
Dynamic values that can affect the behavior of processes in the operating


Which of the following is an automation tool?
Ansible


When does the need for automation arise?
When a sequence of actions requiring accuracy and/or being routine is performed periodically


Which comparison operator is used to check numerical equality?
-eq


What is the difference between single and double quotes when working with strings?
Variables are not interpolated in single quotes, but are interpolated in double quotes


How to create a numeric range in a for loop?
{start..end}


Which syntax is used to get the length of a string in Bash?
${#variable}


Which tool is used for operations with floating-point numbers in Bash?
bc (Basic Calculator)


How to perform arithmetic operations with integers in Bash?
Using double parentheses (( ))


What will happen when executing the command name = "John" with spaces around the equals sign?
An error will occur


Which syntax is used to extract a substring in Bash?
${variable:start:length}


What does the set -e command do?
Terminates script execution on the first error


Which symbol is used in Bash to denote the beginning of a shebang?
#!


Which environment variable defines the list of directories to search for executable files?
PATH


How to declare a local variable inside a function?
local variable_name=value


Which tool is a workflow automation platform built into GitHub?
GitHub Actions


What is automation in the IT context?
Using technologies to perform tasks with minimal human intervention to replace human labor

What does the || operator mean on the command line?
Executes the second command only if the first one failed



What is the crontab -l command used for?
To view current tasks


What does each field mean in the crontab format * * * * * command?
minute hour day_of_month month day_of_week command


What is Git?
Distributed version control system


What is a merge conflict?
Git cannot automatically merge changes from different branches


What does the git add command do?
Prepares files for commit (staging)


What does the abbreviation CI mean in the context of software development?
Continuous Integration


What programming language is used to write Jenkinsfile?
Groovy


How to replace all occurrences of character "o" with "O" in variable text="Hello, World!" in Bash?
Неправильно: echo ${text//o/O}
Мб: ${text//o/O}


How to calculate the sum of two integers a and b in Bash and store the result in variable sum?
Ответ: sum=$((a + b))


How to extract a substring from variable str="Hello, World!" starting at position 7 with length 5 in Bash?
Ответ: ${str:7:5}


How to view current branch?
Ответ: git branch


How to delete local branch feature-old?
Ответ: git branch -d feature-old


What protocol is commonly used for communication with persistent agents on Unix-like systems?
SSH


What block in the declarative syntax defines actions after the pipeline completes in Jenkins?
post


What command is used to execute Windows commands on a Jenkins agent?
bat 'command'


What does agent any mean in the declarative syntax of Jenkins?
The pipeline can run on any available agent


What command is used to execute a shell command on a Linux agent in Jenkins?
sh 'command'


A dynamic Jenkins agent is:
An agent that is created on demand to perform tasks


Which method of using Docker from a Jenkins agent does NOT exist?
Via FTP


Which port is used by Jenkins agents to connect to the controller via JNLP?
50000


Which port is used by the Docker API without TLS?
2375


What is the advantage of permanent agents?
Fast build startup

!
What keyword is used to define variables in Groovy?
def


What type of credentials is NOT supported by Jenkins by default?
Biometric data (fingerprints)


What block defines the execution stages in a declarative Jenkins pipeline?
stages


What built-in variable contains the incrementing number of the current build in Jenkins?
env.BUILD_NUMBER


In which file are Jenkins pipeline definitions usually stored?
Jenkinsfile


What needs to be installed on the agent machine for Jenkins to work?
JRE or JDK


What needs to be installed on the target machine to set up a permanent agent via SSH?
SSH server


What do the base official Jenkins agent images (jenkins/inbound-agent) NOT contain?
Build tools (Maven, Gradle, npm)


Which of the following methods is NOT a way to connect dynamic Jenkins agents?
HTTPS


Why is it not recommended to run builds directly on the controller node?
Builds may gain access to the controller's configuration and data


What Jenkins service manages agents and distributes tasks?
Jenkins controller


What does the when directive do in a declarative Jenkins pipeline?
Defines conditions for executing a stage


What does parallel execution of stages mean in a Jenkins pipeline?
Simultaneous execution of multiple independent stages


What type of parameter is used to select from a predefined list of values in Jenkins?
choice


What section is used to define environment variables in a declarative Jenkins pipeline?
environment


What is the advantage of dynamic agents?
Efficient resource utilization


Which official Jenkins image is recommended for connecting agents via JNLP?
jenkins/inbound-agent


For which types of tasks is it recommended to reserve permanent agents?
For critical tasks


Which URI format is used to connect to the Docker host socket?
unix:///var/run/docker.sock


What is recommended to use for differentiating between different types of builds on agents?
Labels


What block in the post section runs regardless of the build result in Jenkins?
always


What port is used for communication between the Jenkins controller and agents?
50000


What Jenkins service performs build tasks?
Jenkins agent


What programming language is Jenkinsfile written in?
Groovy


Why is it not recommended to run builds on the Jenkins controller node?
Builds may gain access to the controller's configuration


When is it useful to use permanent Jenkins agents?
For long-running or resource-intensive tasks


A permanent Jenkins agent is:
An agent that is always available to perform tasks


Which of the following protocols can be used for communication between the controller and the agent?
JNLP


Which address is used to access the Docker host from a Jenkins container?
host.docker.internal


Which of the following protocols can be used for communication between the controller and the agent?
SSH


Which port is used by the Docker API with TLS?
2376


What is a bottleneck in a CI/CD pipeline?
A stage in the process that limits the overall system performance


What does Amdahl's Law define?
The theoretical limit of speedup when adding computational resources


What method helps optimize the use of CI/CD agents?
Dynamic scaling of agents based on current load


What level of caching includes saving node_modules and other dependencies?
Dependency caching


According to the Pareto principle, what should be the focus during optimization?
On the 20% of processes that provide 80% of the effect


What is a "resource" in Terraform?
The basic building block of infrastructure


What does the terraform plan command do?
Shows the changes that will be applied without executing them


What is GitOps in the context of infrastructure management?
Using Git as the single source of truth for infrastructure


What is a Terraform provider?
A plugin for interacting with a specific platform or service

What is the principle behind immutable infrastructure?
Replacing servers instead of modifying them during updates


What cache invalidation strategy updates the cache at specified time intervals?
Time-based


What metric measures the total time from change initiation to deployment?
Lead Time


What approach helps reduce Docker image build time?
Using multi-stage builds and optimizing layer order


What is parallelization in the context of CI/CD?
Simultaneous execution of independent tasks on different resources


What principle should be applied before starting to optimize a CI/CD pipeline?
Measure before you optimize


What is a Terraform state file?
A file containing information about the current state of the managed infrastructure


What is an Ansible role?
A reusable set of tasks, files, and variables for a specific purpose


What is the advantage of versioning IaC code?
The ability to track infrastructure changes and roll back to previous versions


What is an Ansible module?
A ready-to-use block of code for performing a specific task


What type of tasks does Ansible primarily perform?
Configuration management


What is the limitation of parallelization in CI/CD?
Dependencies between tasks


What is "incremental build" in the context of CI/CD optimization?
Building only the changed components of the system without rebuilding the entire project


What technique helps reduce test execution time?
Categorizing tests and running independent groups in parallel


What does "exploitation of the constraint" mean in the Theory of Constraints?
Maximally efficient use of the bottleneck without additional investments


What does the Throughput metric show in CI/CD?
The number of successfully processed changes per unit of time


Where is the infrastructure state stored by default in Terraform?
In the local file terraform.tfstate


Deployment strategy where two identical production environments are maintained, switching between which ensures safe deployment:
Blue-Green Deployment


What is a Terraform module?
A reusable container for multiple resources in a project


What is Infrastructure as Code (IaC)?
The practice of managing infrastructure through configuration files


Which command initializes a new Terraform project?
terraform init


According to the principles of the Theory of Constraints (TOC), what happens to the system when an hour is lost at the bottleneck?
The entire system loses an hour of productivity


What is the first step in the Theory of Constraints (TOC) optimization cycle?
Identification of the constraint


What does the "fail fast" principle mean in CI/CD optimization?
Performing quick and critical checks at the beginning of the pipeline


What type of caching is based on the hash of the dependency file?
Content-based caching


What happens if you speed up a stage that is NOT a bottleneck?
The overall system performance does not change


Which approach describes the desired state of the infrastructure, and the system itself determines how to achieve it?
Declarative


What is idempotence in the context of IaC?
A property of an operation where repeated execution does not change the result


What is provisioning in the context of IaC?
Automatic creation and configuration of infrastructure resources


Which language is used in Terraform to describe infrastructure?
HCL


What is "drift detection" in IaC?
Detecting discrepancies between the code and the actual state of resources


Which IaC tool uses YAML language and works without agents on target systems?
Ansible


What does the DRY principle mean in the context of IaC?
Don't Repeat Yourself


Ansible file containing a list of target hosts and their grouping for management:
Inventory


What is an Ansible playbook?
A YAML file describing tasks to be executed on hosts


What is the Zero Trust principle?
No system component is trusted by default


Which of the following methods of storing secrets is the least secure?
In the application source code


How is it recommended to pass secrets in a Jenkins pipeline?
Through the Credentials Store using credentials()


What is the purpose of auditing automation systems?
Checking compliance with security standards and regulatory requirements


What is the recommended rotation frequency for database credentials?
Every 90 days


What deployment approach uses a pull model?
GitOps


What is Infrastructure as Code (IaC)?
Describing infrastructure as version-controlled code


What are Blameless Post-Mortems?
Incident analysis without blaming, focusing on systemic causes


What is ADR in the context of documentation?
Architecture Decision Records


Which environment is intended for end users and requires high availability?
Production environment


What is a "data subject" according to GDPR?
An individual whose personal data is processed


Which tool is used to prevent adding secrets to a Git repository?
git-secrets


What is secret rotation?
Regularly changing secrets to limit the lifetime of compromised data


What measure prevents the execution of malicious code through user input?
Validation of data type and format before processing


What principle requires granting only the necessary access rights to scripts?
Principle of Least Privilege


What is Contract Testing in microservices architecture?
Checking API compatibility between services


What does SAST mean in the context of Shift-Left Security?
Static Application Security Testing


What is Blue-Green Deployment?
Maintaining two identical environments for safe deployment


What principle means breaking work into minimal viable changes?
Small Batch Size


What does idempotency of operations mean in IaC?
Reapplying does not change the system from the desired state


What method is recommended to prevent SQL injection?
Parameterized queries


What Bash command sets strict mode for script execution?
set -euo pipefail


What is network segmentation?
Dividing the network into isolated segments with controlled interaction


What is RoPA in the context of GDPR?
Record of Processing Activities


Which GDPR principle requires collecting only necessary data?
Data minimization


What does Configuration Drift mean?
Divergence of environments due to manual changes


What is GitOps?
Git as the single source of truth for system state


What are Feature Flags?
A mechanism to control functionality through configuration


What are Canary Releases?
Gradual deployment of a new version with metric monitoring


What does the Fail Fast principle mean?
Quickly detecting and responding to errors during development


What is a `.env` file?
A file for storing environment variables


What is Defense in Depth?
Applying multiple layers of protection


Which file should be used to prevent secrets from being committed to Git?
.gitignore


What should be implemented in CI/CD pipelines to comply with the Storage Limitation principle?
Mechanisms for automatic data deletion after expiration


What does the abbreviation GDPR stand for?
General Data Protection Regulation


What is Trunk-Based Development?
Development on the main branch with short-lived feature branches


What is the Test Pyramid in testing strategy?
Many unit tests at the base, fewer integration tests, and minimal end-to-end tests


What is NOT a pillar of Observability?
Dashboards


What does the CAMS model in DevOps represent?
Culture, Automation, Measurement, Sharing


What does Shift-Left Security mean?
Integrating security practices early in the development process


What approach is recommended for input validation?
Using allowlists (whitelists) of permitted values


What does the scope of CI/CD pipeline auditing include?
Assessing the security and efficiency of continuous integration and delivery processes


What is HashiCorp Vault?
A centralized secrets management system


What is Path Traversal vulnerability?
Attempt to access files outside the allowed range using `../`


What data should be encrypted in secure environments?
Data at rest and in transit


What is NOT a key DORA metric for evaluating DevOps?
Code Coverage


Which CAMS principle focuses on knowledge sharing?
Sharing


What problem arises from inverting the Test Pyramid?
Many slow e2e tests make the pipeline slow and unstable


What does the Immutable Artifacts principle mean?
An artifact is created once and used across all environments without changes


What is the name of the section in a declarative pipeline that runs after all stages have completed?
Ответ: post


What built-in variable contains the full URL of the current build?
Ответ: BUILD_URL


What Docker image is officially recommended for running Jenkins?
jenkins/jenkins:lts


What type of parameter allows a user to select a value from a dropdown list?
choice


How to view repository status?
Ответ: git status


How to add file login.js to tracking?
Ответ: git add login.js


Which CI/CD tool is originally designed as a self-hosted solution and requires installation on own servers?
Jenkins


How to create file config.txt with content APP_NAME=app in the terminal?
Ответ: echo "APP_NAME=app" > config.txt


Which variable contains the number of arguments passed to the Bash script?
$#


What to do if a UnicodeDecodeError occurs when reading a file in a Python script?
Try a different encoding or handle the exception


What data is recommended to include in logs to simplify analysis?
Timestamp, severity level, message, process identifier, metadata


What is a Pull Request (Merge Request)?
Request to merge changes from one branch to another with code review capability


What is the difference between git pull and git fetch?
pull gets changes and automatically merges them, fetch only gets


Which stage usually does NOT belong to a standard CI/CD pipeline?
Application architecture planning


What built-in variable contains the name of the job in Jenkins?
Ответ: JOB_NAME


What command in Groovy is used to print text to the Jenkins console?
Ответ: echo


Through which object is access to environment variables in a Jenkins pipeline provided?
Ответ: env


What built-in variable contains the path to the workspace directory of the current build?
Ответ: WORKSPACE


How to add directory /opt/myapp/bin to the PATH variable in Bash?
Ответ: export PATH="/opt/myapp/bin:$PATH"


How to push local commits to remote repository?
Ответ: git push


How to get all changes from remote repository and merge immediately?
Ответ: git pull


What is the difference between while and until loops in Bash?
while executes while the condition is true, until - while the condition is false



What does the */15 * * * * entry mean in crontab?
Execute every 15 minutes


Which Python block is used for proper exception handling in automation?
try-except


Which command creates a new branch and immediately switches to it?
git checkout -b <branch-name>


What does the git gc command do?
Optimizes repository by removing unnecessary objects


What is rebase in Git?
Rewriting commit history to create a more linear history


What three phases does each CI/CD pipeline stage include?
Preparation, execution, result processing


What are the three main components described in GitHub Actions workflow?
Events, jobs, steps


What is the name of the built-in variable that contains the current build number?
Ответ: BUILD_NUMBER


What will happen when executing the command name = "John" with spaces around the equals sign in Bash?
An error will occur


Which construct is used to check multiple conditions in if statements in Bash?
elif


How to declare a local variable inside a function in Bash?
local variable_name=value


Which operator checks that a file exists and is a regular file in Bash?
-f


Which comparison operator is used to check numerical equality in Bash?
-eq


What does os.makedirs(path, exist_ok=True) mean in Python?
Creates directory with all parent folders, ignoring if it already exists


What does the crontab entry 0 2 * * * /home/user/backup.sh mean?
Execute every day at 2:00 AM


Which tools can be used for automatic log analysis?
grep, awk, sed


Which command is used to edit the current user's crontab?
crontab -e


What does the parameter sum(1 for _ in f) mean in Python when counting file lines?
Efficiently counts lines without loading the entire file into memory


What role do cloud platforms play in team development?
Collaboration tools, version control, CI/CD pipelines


What advantages does Web API integration provide in CI/CD?
Linking GitHub, GitLab, Jenkins; integration with code analysis tools; project management synchronization


When should Python be used instead of Bash for automation?
When working with complex data structures (JSON, XML), network requests, exception handling


What is Web API in the context of automation?
A mechanism for integrating disparate services into a unified ecosystem


Which HTTP method is commonly used to retrieve data through REST API?
GET


Where does the cron scheduler look for crontab files?
In /var/spool/cron, /etc/anacrontab, /etc/cron.d


What approaches are used for effective error handling in automation?
Error logging, notifications, retry attempts, fallbacks


Which Python module is best suited for logging configuration?
logging


Which Python module is used for copying files?
shutil


What main software development processes can be automated?
Workplace setup, build, deployment and testing


Which command adds a file to Git tracking?
git add <filename>


What does the git fetch command do?
Gets updates from remote repository without automatic merging


What is the modern recommended command for switching between branches (Git 2.23+)?
git switch


What does SHA-1 hash mean in Git context?
Unique commit identifier


What does the git diff command show?
Differences between working directory and last commit


Which command is used to create a commit in Git?
git commit -m "message"


Which command shows the current state of the working directory?
git status


Command for undoing changes in the working directory?
git restore


What is the git remote add origin <url> command used for?
Adds a remote repository named origin


Which command is used to view commit history?
git log


Which command is used to initialize a new Git repository?
git init


What is the foundation of Git architecture?
Directed Acyclic Graph (DAG)


What information must be configured during initial Git setup?
Username and email


What is git stash used for?
Temporarily saving unfinished changes


What happens when executing the git clone command?
Creates a complete local copy of the remote repository


Which file is used to exclude files from Git tracking?
.gitignore


For which types of files is Git LFS recommended?
Large binary files (media, archives)


What is Command Injection?
Injection of system commands through user input


What GDPR principle requires data to be collected only for specific purposes?
Purpose limitation


Пример Jenkinsfile:
pipeline {
    agent { label 'php-agent' }

    stages {
        stage('Checkout') {
            steps {
                echo 'Cloning repository...'
                checkout scm
            }
        }

        stage('Install Dependencies') {
            steps {
                echo 'Installing dependencies...'
            }
        }

        stage('Test') {
            steps {
                echo 'Running PHP tests...'
                sh 'php -v'
                sh 'echo "Simulated tests passed!"'
            }
        }
    }

    post {
        always {
            echo 'Pipeline completed.'
        }
        success {
            echo 'All stages completed successfully!'
        }
        failure {
            echo 'Pipeline failed — please check logs.'
        }
    }
}




Пример Jenkins Pipeline:
pipeline {
    agent any
    parameters {
        choice(
            name: 'ENVIRONMENT', 
            choices: ['dev', 'staging', 'prod'], 
            description: 'Target environment for deployment'
        )
        booleanParam(
            name: 'SKIP_TESTS', 
            defaultValue: false, 
            description: 'Skip test execution'
        )
        string(
            name: 'VERSION', 
            defaultValue: '1.0.0', 
            description: 'Version for deployment'
        )
    }
    stages {
        stage('Deploy') {
            steps {
                script {
                    // Using parameters in pipeline logic
                    if (!params.SKIP_TESTS) {
                        sh 'npm test'
                    }
                    sh "echo Deploying version ${params.VERSION} to ${params.ENVIRONMENT}"
                }
            }
        }
    }
}



Example of a simple Jenkinsfile that performs application building, testing, and deployment:
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'npm ci'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
                sh 'npm test'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
                sh 'npm run build'
            }
        }
    }
    post {
        success {
            echo 'Pipeline completed successfully!'
        }
        failure {
            echo 'Pipeline failed.'
        }
    }
}



Initialization and Configuration:
git init — Initialize new local repository
git clone <url> — Clone remote repository
git config — Configure Git parameters

Change Management:
git status — Analyze current working directory state
git add <file> — Prepare files for commit (staging)
git commit -m "message" — Record changes with descriptive message
git log — View commit history with detailed information

Branch Operations:
git branch — Branch management (view, create, delete)
git switch <branch> — Switch between branches (modern approach, recommended with Git 2.23+)
git checkout <branch> — Switch between branches (classic approach, universal command)
git merge <branch> — Integrate changes from specified branch

Remote Repository Synchronization:
git remote — Manage remote repositories
git fetch — Get updates without automatic merging
git pull — Get and automatically integrate changes
git push — Publish local changes to remote repository



cron:
* * * * * /path/to/command arguments
| | | | | |
| | | | | +------ Command to execute
| | | | +-------- Day of the week (0 - 7) (Sunday = 0 or 7)
| | | +---------- Month (1 - 12)
| | +------------ Day of the month (1 - 31)
| +-------------- Hour (0 - 23)
+---------------- Minute (0 - 59)


Example:
# Start backup at 2 AM daily
0 2 * * * /home/user/backup.sh
# Clear temporary files every hour
0 * * * * rm -rf /tmp/*



Example 1. File Backup
#!/bin/bash
# first argument is source file, second is destination
if [ "$#" -ne 2 ]; then
  echo "Usage: $0 source_file destination_file"
  exit 1
fi

src="$1"
dest="$2"

cp "${src}" "${dest}"

if [ "$?" -eq 0 ]; then
  echo "Backup successful"
else
  echo "Backup failed"
fi


Example 2. Counting lines in a file
#!/bin/bash

if [ "$#" -ne 1 ]; then
  echo "Usage: $0 file"
  exit 1
fi

file="${1}"

if [ ! -f "${file}" ]; then
  echo "File not found!"
  exit 1
fi

lines=$(wc -l < "${file}")

if [ "$?" -ne 0 ]; then
  echo "Error reading file"
  exit 1
fi

echo "Number of lines: ${lines}"


Example 3. Counting lines in a file, functional style
#!/bin/bash

function count_lines() {
  local file="$1"
  lines=$(wc -l < "${file}")
  if [ "$?" -ne 0 ]; then
    echo "Error reading file"
    return 1
  fi
  echo "${lines}"
  return 0
}

if [ "$#" -ne 1 ]; then
  echo "Usage: $0 file"
  exit 1
fi

if [ ! -f "${1}" ]; then
  echo "File not found!"
  exit 1
fi

result=$(count_lines "${1}")
echo "Number of lines: ${result}"



Example 4. Merging multiple text files into one
#!/bin/bash
if [ "$#" -lt 2 ]; then
  echo "Usage: $0 output_file input_file1 [input_file2 ...]"
  exit 1
fi
output_file="${1}"
shift
cat "$@" > "${output_file}"
if [ "$?" -eq 0 ]; then
  echo "Files merged into ${output_file}"
else
  echo "Error merging files"
fi



Закон Амдала и параллелизация
Формула закона Амдала:
Ускорение = 1 / ((1 - P) + P/N)
Где:
P = доля процесса, которую можно распараллелить (от 0 до 1)
N = количество параллельных потоков/процессоров
(1 - P) = последовательная (нераспараллеливаемая) часть



Примеры параллелизации в Jenkins:
// Параллельное выполнение тестов
pipeline {
    agent any
    stages {
        stage('Parallel Tests') {
            parallel {
                stage('Unit Tests') {
                    steps {
                        sh 'npm run test:unit'
                    }
                }
                stage('Integration Tests') {
                    steps {
                        sh 'npm run test:integration'
                    }
                }
                stage('E2E Tests') {
                    steps {
                        sh 'npm run test:e2e'
                    }
                }
            }
        }
    }
}
