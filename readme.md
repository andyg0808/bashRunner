# Introduction
**bashRunner** is a set of convenient bash functions that together can run a
group of bash functions with pretty output.

It can also be used to only run a task once, using dconf to store whether the
current user has run the task yet.

It was created one night when I had solved a problem with Ubuntu's Unity by
setting some configuration information, but needed to do the same on all the
user accounts for the system. Rather than forcing my way into each account as
root, I took the longer way around and wrote a tool. So now, when a user who
hasn't had the config applied yet logs into their account, this tool is run and
applies the config. The onetime capability lets me only run the task on that
first login.

# Description
Look at the (one) script file. Starting about line 98 there's a bunch of config
information.


-----

bashRunner: a simple task runner written in Bash
Copyright 2013 Andrew Gilbert

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
