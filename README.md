# 🎓 Campus Network Infrastructure Documentation

## 📌 Overview

Dokumentasi implementasi jaringan kampus menggunakan MikroTik, VLAN, dan FreeRADIUS untuk autentikasi terpusat berbasis WPA2/WPA3 Enterprise (802.1X).

## 🚀 Features

* VLAN segmentation (Staff, Student, Guest)
* Centralized authentication (FreeRADIUS)
* WPA2/WPA3 Enterprise (802.1X)
* Scalable network design

## 🛠️ Tech Stack

* MikroTik RouterOS
* FreeRADIUS
* VLAN (802.1Q)
* Linux Server

## 🏗️ Network Topology

![Topology](docs/images/topology.png)

## 📂 Documentation

* [Network](docs/network/vlan.md)
* [MikroTik](docs/mikrotik/basic.md)
* [RADIUS](docs/radius/config.md)

## 💡 Case Study

### Problem

User tidak mendapatkan IP address saat terhubung ke WiFi

### Root Cause

DHCP tidak terkonfigurasi dengan benar pada VLAN terkait

### Solution

* Validasi interface VLAN
* Perbaikan DHCP server binding

### Result

User berhasil mendapatkan IP sesuai segmentasi VLAN

## 👨‍💻 Author

Enggar Irawan
Network Engineer Enthusiast
