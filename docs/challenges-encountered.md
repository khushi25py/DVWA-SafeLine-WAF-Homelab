# Challenges Encountered

## SafeLine Installation Delay

### Problem

SafeLine services remained in a waiting state during installation.

### Resolution

Verified Docker installation and allowed all containers to complete health checks.

---

## SSL Certificate Upload Issues

### Problem

Certificate files stored under protected Linux directories could not be uploaded directly.

### Resolution

Copied certificate and key files to a user-accessible location before importing into SafeLine.

---

## Reverse Proxy Configuration

### Problem

The Ubuntu default Apache page was displayed instead of DVWA.

### Resolution

Verified backend connectivity and corrected SafeLine upstream configuration.

---

## DNS Resolution

### Problem

The hostname [www.dvwa.local](http://www.dvwa.local) was not resolving correctly.

### Resolution

Configured Windows and Kali hosts files with the Ubuntu server IP address.

---

## SQL Injection Validation

### Problem

Needed to verify whether SafeLine was actively inspecting traffic.

### Resolution

Executed SQL Injection payloads and confirmed detection through SafeLine attack logs.
