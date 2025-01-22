# Security

Security Project

This project implements security models and access control policies, including the Bell-LaPadula model and the Ring policy. The goal is to analyze, test, and demonstrate the principles of secure system design and behavior.

Project Structure
	•	src: Contains the main source code.
	•	Ring.py: Implements the Ring security policy.
	•	acpolicy.py: Core functionalities for access control policies.
	•	BellLaPadula.py: Implementation of the Bell-LaPadula model.
	•	tests: Contains test scripts to verify the system’s behavior.
	•	test.py: General test cases.
	•	testRing.py: Specific tests for the Ring policy.
	•	policies: Contains policy files used by the system.
	•	Ring.policy: Defines rules for the Ring model.
	•	BellLaPadula.policy: Defines rules for the Bell-LaPadula model.
	•	events: Contains example event files for testing.
	•	example1.events: Sample events for system testing.
	•	example2.events: Additional example events.

Features
	1.	Bell-LaPadula Model:
	•	Ensures confidentiality by enforcing “no read-up” and “no write-down” rules.
	2.	Ring Policy:
	•	Implements flexible access control rules based on predefined policies.
	3.	Testing Framework:
	•	Includes scripts and event files to verify system behavior.

How to Use:

	1.	Clone this repository:

git clone https://github.com/MKx6/Security.git  


	2.	Navigate to the directory:

cd Security  


	3.	Run the tests:

python tests/test.py  
python tests/testRing.py  

Contributions:
This project was a collaborative effort by:
	•	Maryam Matar
	•	Ghezlan Alotaibi

We worked together to design and implement this project, focusing on applying security principles effectively.

License

This project is licensed under the GNU General Public License (GPL). You are free to use, modify, and distribute the code as long as any derivative works remain open-source and licensed under the same terms.

For more details, refer to the LICENSE file in this repository.
