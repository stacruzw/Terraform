# Terraform first project

resource "aws_instance" "firstproject" {

  ami           = "ami-027cab9a7bf0155df"

  instance_type = "t2.micro"



  tags = {

    name = "demoinstance"

  }

}



