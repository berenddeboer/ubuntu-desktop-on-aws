# Not working

Unfortunately I haven't been able to get this working: it appears
impossible with Ubuntu 18.04 to enable remote screen sharing.

You can still start X programs though, through `ssh- X` but you won't
have access to a regular desktop session.

If anyone knows a fix, please!


# Introduction

This ansible script creates a Ubuntu desktop on AWS.


# Requirements

- Ansible 2.4
- Make sure EC2_REGION variable is set
