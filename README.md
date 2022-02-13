# CloudComputing-A1
Assignment Submission for Assignment 1
Assignment link [https://webserver-cs4843-samuelhennon.s3.amazonaws.com/index.html]
#==================================================<Main Dev Process 
#=========================<Bucket Properties
Bucket Versioning : Enabled
Static Website Hosting : Enabled
Hosting Type : Bucket Hosting
#=========================<Bucket Permissions
Block all public access : off
#==========<Bucket Policy
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadGetObject",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::webserver-cs4843-samuelhennon/*"
        }
    ]
}
#=========================<Html Setup
I personally used Visual Studio Code with an extension called live server for most of the live devolpment of the webpage and it was super useful having never touchted html before
#==========<File Setup
The index file feeds into the five other pages all about a different component found in a computer these are listed as
* cpu.html
* gpu.html
* psu.html
* ram.html
* ssd.html


All of these have .jfifs with respective matching names to the file showing a photo of the part in mention
examle for cpu.html the file name would be cpu.jfif this is for orginization help and ease of development

#==========<Component pages
                      
All of the component pages have a photo and a button leading to their respcive wiikipedia pages of the component as well as a button labled home leading to index.html
#=========================<Closing

This is my first time both using github and touching anything related to web development as well as touching in html so please if you have any feedback on the code or this readme let me know
Thanks
Samuel Hennon

#==================================================<Fin
