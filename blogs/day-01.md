# Trusted Guardian — Day 1

**Date:** 8 November 2026

## What I Did

Today I started the technical foundation of **Trusted Guardian** by building the first machine of my security laboratory.

I downloaded the Ubuntu 24.04 ISO and used it to create my first virtual machine in VirtualBox, named `guardianai1`. This VM will become the starting point for the Guardian environment.

## What I Learned

Today I learned how a virtual machine is built from an installation image: the ISO acts as the installer, and the hypervisor provides virtual hardware such as CPU, memory, disk, and network adapters.

I also understood why a virtual lab matters for security work. A VM is isolated from my main system, so I can experiment, make mistakes, and later test attacks safely, without risking my host machine.

## Key Takeaway

**A safe, isolated environment is the foundation of security research.**

## Next

Next I will configure the lab network and prepare a second machine that will act as the monitored target, so the Guardian has something to observe.
