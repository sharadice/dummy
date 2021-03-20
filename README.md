# Why add a default, publicly available "Sharadice Dummy Package" in this respository?

Alex Birsan described a serious security vulnerability that affects package managers for most modern languages, 
including Composer. In short, the issue is that the package manager usually checks the default publicly 
available package repository which allows malicious users to substitute the legitimate package 
hosted on a private repository.
