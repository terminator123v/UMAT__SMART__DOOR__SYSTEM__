# UMAT__SMART__DOOR__SYSTEM__
UMAT__SMART__DOOR__SYSTEM
# Smart Door Access System for UMaT

This repository contains a Python implementation of a smart door access system designed for UMaT admin staff. The project illustrates encapsulation concepts, ensuring that sensitive data such as staff access codes are protected from unauthorized direct access or modification.

## Design Highlights
- Encapsulation: Private attributes are prefix-named with double underscores (__access_code) to leverage Python's name mangling.
- Properties: The @property decorator manages access to the private attribute, replacing traditional getter/setter methods.
- Validation: Strict checks are implemented to validate the length of the access code before allowing any modifications.
- Authorization: The view_access_code method enforces role-based security to ensure that only authorized roles (e.g., Dean, Admin) can view sensitive credentials.

## How to Run

To run the program, ensure you have Python installed and execute:

`bash
python smart_door.py
