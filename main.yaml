terraform {
    required_providers {
      aws = {
        source = "hashicorp/aws"
        version = "~> 4.s"
      }
    }
}

provider "aws" {
   
  region = "ap-south-1"
}
resource "aws_vpc" "myvpc_new" {
  cidr_block = "10.1.0.0/16"
  instance_tenancy = "default"
  tags = {
    Name = "mydemovpc"
  }
}