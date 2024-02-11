# Crash Analyzer Project

The Crash Analyzer project is a system developed internally at Parallel Wireless aimed at enhancing crash identification processes while maintaining confidentiality. The project leverages Docker and parallel programming to optimize crash detection, reducing identification time by 50%. It also includes innovative mechanisms for new crash detection and features a user-friendly frontend interface for efficient monitoring containing crash record statistics.

## Key Features

- **Crash Identification Efficiency**: Utilizes Docker and Celery to streamline crash identification, resulting in a 50% reduction in identification time.

- **New Crash Detection**: Identification of crash using s3 bucket.

- **User-Friendly Frontend Interface**: Provides an intuitive platform for monitoring crashes and associated metrics across different setups.

- **LDAP Integration for Notification Registration**: Integrated with LDAP for seamless notification registration, ensuring timely alerts for critical crash events and facilitating proactive monitoring.

## Getting Started

To utilize the Crash Analyzer project:

1. Clone the repository to your local machine.
2. Install Docker, Nodejs, MongodB, React, Nginx, Redis and Celery, if not already installed.
3. Configure environment variables and settings.
4. Build and deploy Docker containers using provided configuration files.
5. Access the frontend interface through the provided URL to commence monitoring crashes and associated metrics.

## High Level Diagram
![image](https://github.com/snanadi/crash_detection/assets/159690874/eb8687ad-6824-42d5-8952-3d191c01f17f)

