# Enterprise Cloud Infrastructure Portfolio
**Focus:** AWS Architecture, Terraform Automation, and DevSecOps Integration.

## Phase 1: Linux Foundation & Core Security
*Objective: Establish secure local environments prior to cloud deployment.*

### Module 1: Directory Architecture
Established local file system hierarchy for future code repositories.
* Utilized `pwd`, `ls`, `mkdir`, and `cd` to construct and navigate the baseline directory structure without a graphical interface.
* Created baseline text files using `touch`.

### Module 2: File Permissions & Security (Zero-Trust Basics)
Manipulated Linux security perimeters to isolate files from unauthorized system users.
* Audited default system permissions using `ls -l`.
* Executed octal permission modifications using `chmod`.
* **Execution Proof:** Successfully converted a standard text file into an executable Bash script and bypassed the kernel's default execution block by applying `chmod 700` (granting strict Owner-only Read/Write/Execute authority).

### Module 3: Text Manipulation & Log Analysis
Simulated enterprise log extraction and data filtering pipelines.
* Generated mock infrastructure logs utilizing `echo` and redirection operators (`>`).
* Retrieved and audited raw data using `cat`, `head`, and `tail`.
* **Execution Proof:** Successfully constructed a data pipeline using `grep` and the pipe operator (`|`) to instantly isolate the most recent critical system failure from a continuous text stream.
