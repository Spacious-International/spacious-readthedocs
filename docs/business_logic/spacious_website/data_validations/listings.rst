********
Listings
********


building
========
- Presence Validation


net_area
========
- Presence Validation

  - Enabled when **ALL** of following conditions are **false**:

    - Linked to a project (building) record for overseas marketing
    - Marked as village house property

- Numeral Range Validation

  - Minimum value: 1


gross_area
==========
- Presence Validation

  - Enabled when **ALL** if following conditions are **true**:

    - **Not** linked to a project (building) record for overseas marketing
    - Marked as village house property

- Numeral Range Validation

  - Minimum value: 1


bedrooms_count
==============
- Numeral Range Validation

  - Minimum value: 0
  - Maximum value: 10


bathrooms_count
===============
- Numeral Range Validation

  - Minimum value: 0


parking_count
=============
- Numeral Range Validation

  - Minimum value: 0


agent_license_number
====================
- Presence Validation

  - Enabled when **ALL** if following conditions are **true**:

    - Created by agent/agency
    - Related to one of following cities:

      - Taipei
      - Singapore


contact_name
============
- Presence Validation

  - Enabled when **ALL** if following conditions are **true**:

    - Created by agent/agency
    - Related to one of following cities:

      - Singapore


contact_phone
=============
- Presence Validation

  - Enabled when **ALL** if following conditions are **true**:

    - Created by landlord users


contact_email
=============
- Presence Validation

  - Enabled when **ALL** if following conditions are **true**:

    - Created by landlord users


price
=====
- Presence Validation
- Numeral Range Validation

  - Minimum value: 1

    - Enabled when **ALL** of following conditions are **false**:

      - Value equals ``-1000000001`` (special value for other meaning)

  - Maximum value: 9223372036854775807


remote_reference_id
===================
- Presence Validation

  - Enabled when **ALL** of following conditions are **false**:

    - "Posted directly" (listing created through website/mobile lister app/spreadsheet)


user (poster user)
==================
- Presence Validation

  - Enabled when **ALL** of following conditions are **false**:

    - "Posted directly" (listing created through website/mobile lister app/spreadsheet)
