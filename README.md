# My-terraform-notes-TCK
# Terraform
Work station Manangement tool // or // Infra Building and Managing tool or It can be known as Orchestration Management Tool.It works on Cloud Platform.
Developed by Mitchell Hashimoto, Its backend coding is written in Go language.

# Commands, Syntax and components
Provider == for which provider you are going to create infra like aws , azure etc as terraform is supporting around 100+ provider.
Example 
provider "aws" {
region = "us-east-1"
access_key = ""
secret_key = ""
}
For Resource 
resource "aws_instance" "nameofchoice" {
ami = "ami id or u can given ref by using data parameter"
instance_type = "t3a.micro"
}
