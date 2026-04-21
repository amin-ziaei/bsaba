# Infrastructure Resources Plan (Medium / Test Setup)

## Machines Overview

| Machine Name  | CPU (Cores) | RAM (GB) | Disk 1 (GB) | Disk 2 (GB) | Disk 3 (GB) | OS             | Private IP | Public IP |
|---------------|------------|----------|-------------|-------------|-------------|----------------|------------|-----------|
| k8s-master-1  | 4          | 8        | 50          | -           | -           | Ubuntu-24.0.4  | 1          | 0         |
| k8s-master-2  | 4          | 8        | 50          | -           | -           | Ubuntu-24.0.4  | 1          | 0         |
| k8s-master-3  | 4          | 8        | 50          | -           | -           | Ubuntu-24.0.4  | 1          | 0         |
| k8s-worker-1  | 16         | 24       | 80          | 50          | 40         | Ubuntu-24.0.4  | 1          | 0         |
| k8s-worker-2  | 16         | 24       | 80          | 50          | 40           | Ubuntu-24.0.4  | 1          | 0         |
| k8s-worker-3  | 16         | 24       | 80          | 50          | 40           | Ubuntu-24.0.4  | 1          | 0         |
| k8s-worker-4  | 16         | 24       | 80          | 50          | 40           | Ubuntu-24.0.4  | 1          | 0         |
| k8s-haproxy-1 | 2          | 4        | 50          | -           | -           | Ubuntu-24.0.4  | 1          | 0         |
| k8s-haproxy-2 | 2          | 4        | 50          | -           | -           | Ubuntu-24.0.4  | 1          | 0         |
| db-1          | 4          | 8        | 60          | -           | -           | Ubuntu-24.0.4  | 1          | 0         |
| db-2          | 4          | 8        | 60          | -           | -           | Ubuntu-24.0.4  | 1          | 0         |
| db-3          | 4          | 8        | 60          | -           | -           | Ubuntu-24.0.4  | 1          | 0         |
| nginx-1,2       | 2          | 4        | 50          | -           | -           | Ubuntu-24.0.4  | 1          | 1         |
| gitlab-1      | 4          | 8        | 50          | -           | -           | Ubuntu-24.0.4  | 1          | 0         |
| registry-1    | 4          | 8        | 50          | -           | -           | Ubuntu-24.0.4  | 1          | 0         |