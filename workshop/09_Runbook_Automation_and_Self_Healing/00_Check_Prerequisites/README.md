# Check Prerequisites

## Data needed

- You personal license for Ansible Tower (Confirm with instructor)

## Steps

1. In case you don't have your license yet, you can get a free license here: [https://www.ansible.com/license]
2. To avoid unnecessary issue detection and problem generation for transactions and services, complete the following steps:
    - Go to Settings, Anomaly Detection, Frequent issue detection, and click on the button next to Detect frequent issues within transactions and services to disable it.
    - Click on Save Changes

![Disable Frequent Issue Detection](./assets/frequent_issue_detection.png)

## Troubleshooting

1. If at any point you struggle with having production properly deployed, fixProduction.sh is a script that will recreate production for you. Please chmod +x fixProduction.sh, and start at the top with Lab 09.

Execute with:

```
./fixProduction.sh
```

---

:arrow_forward: [Next Step: Deploy Ansible Tower](../01_Deploy_Ansible_Tower)

:arrow_up_small: [Back to overview](../)

[https://www.ansible.com/license]:https://www.ansible.com/license  
