# Welcome!

Welcome to the NewDarwin project! This is, as the name suggests, yet another Darwin derived OS project.

Albeit unintentional, NewDarwin serves as a spiritual successor to PureDarwin, additionally aiming for API parity with Apple on many low-level system components, alongside extending and improving upon the existing codebases provided by Apple.

## What is NewDarwin based on?

The current target for NewDarwin is to build using the released source code for macOS Catalina 10.15.6, otherwise known as Darwin 19.6

## Goals for the project

Currently, the project has two key major targets:
1. Build a minimal system image
2. Get it booting on live hardware

This is then further dividied into numerous projects and targets:
1. Build a working toolchain
2. Build a fresh bootloader that supports newer kernel features, such as the Kext Collection format and KASLR.
3. Upgrade the kernel to support more hardware
4. Build a fresh userspace, with a new libxpc implementation and new utilities and libraries built from the ground up for Darwin

## How do I build NewDarwin?

Apple's own source releases are complicated to build, and require intense research to properly build.

A full system build is complicated, time costly and overall an annoyance, even with advancements in earlier years such as darwinbuild.

A newer build system is on the way! It remains closed for now, but will be released when it's ready.

## AI 'Policy'

Software itself is a form of art, just as we consider paintings art. AI generated code is not art, nor does it have soul.

The joy of creation is what is valued, over the soullessly prompted code that one gets out of AI models such as Claude or ChatGPT.

AI-generated code is not welcome, and will be rejected upon PR.
