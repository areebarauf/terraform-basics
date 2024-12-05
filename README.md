# Terraform Installation Guide

<h1 style="color:blue;">Installation Guide</h1>

<h2 style="color:blue;">Step 1: Install Terraform</h2>
<p>Follow the instructions below to install Terraform based on your operating system.</p>

<h3 style="color:blue;">For Windows</h3>
<ol>
  <li>Download the Terraform binary.</li>
  <li>Visit the official installation page: <a href="https://developer.hashicorp.com/terraform/install">Terraform Installation Guide</a></li>
  <li>Select and download the binary appropriate for Windows.</li>
</ol>

<h3 style="color:blue;">For Linux</h3>
<ol> 
    <li>Run the following commands to install Terraform:</li> 
</ol>

```bash
wget -O - https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg
echo "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list
sudo apt update && sudo apt install terraform

<h3 style="color:blue;">For macOS</h3>
<ol>
  <li>Use Homebrew to install Terraform:</li>
</ol>

brew tap hashicorp/tap
brew install hashicorp/tap/terraform

