---
_enabled_editors:
  - visual
  - content
_inputs:
  staff:
    type: array
  profile_picture:
    type: image
_structures:
  staff:
    style: modal
    values:
      - label: Employee
        icon: support_agent
        preview:
          image:
            - key: profile_picture
            - image
          icon: support_agent
          text:
            - key: name
            - Employee
          subtext:
            - key: description
            - Description of position
        value:
          _type: Employee
          name:
          description:
          profile_picture:
      - label: Manager
        icon: face
        preview:
          image:
            - key: profile_picture
            - image
          icon: face
          text:
            - key: name
            - Manager
          subtext:
            - key: description
            - Description of position
        value:
          _type: Manager
          name:
          description:
          profile_picture:
          url:
staff:
  - _type: Employee
    name: Karen Key
    description: Karen is our Regional Coordinator!
    profile_picture: /images/team/4.jpg
  - _type: Employee
    name: Billy Mills
    description: Billy is our Marketing Associate!
    profile_picture: /images/team/1.jpg
  - _type: Manager
    name:
    description:
    profile_picture:
    url:
  - _type: Employee
    name:
    description:
    profile_picture:
---
