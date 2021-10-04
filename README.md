# NRC7292 OpenWRT Package

## Notice
- (10/04/2021) initial version upload

## Introduction

OpenWrt (OPEN Wireless RouTer) is an open source project for embedded operating systems based on Linux, primarily used on embedded devices to route network traffic. All components have been optimized to be small enough to fit into the limited storage and memory available in home routers.

OpenWrt is configured using a command-line interface (ash shell), or a web interface (LuCI). There are about 3500 optional software packages available for installation via the opkg package management system.

![OpenWrt Login Screen](/images/openwrt_login.png)

## Device Configuration

An RPi3 host is required to run OpenWrt on an NRC7292 module. The DIP switch on the module must be set to HHLLLH.

![OpenWrt Device and DIP Switch Configuration](/images/nrc7292_openwrt_dip_conf.png)

## Start Guide for Image Building

Refer to chapter 2 of [UG-7292-012-OpenWRT.pdf](https://github.com/newracom/nrc7292_openwrt/package/UG-7292-012-OpenWRT.pdf)
