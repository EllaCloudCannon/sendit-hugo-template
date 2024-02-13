---
_enabled_editors:
  - visual
  - content
_inputs:
  staff:
    type: array
  profile_picture:
    type: image
  job_description:
    type: textarea
_structures:
  staff:
    style: modal
    values:
      - label: Employee
        icon: support_agent
        preview:
          image:
            - key: profile_picture
          icon: support_agent
          text:
            - key: name
            - Employee
          subtext:
            - key: job_description
            - Description of position
        value:
          _type: Employee
          name:
          job_description:
          profile_picture:
      - label: Manager
        icon: face
        preview:
          image:
            - key: profile_picture
          icon: face
          text:
            - key: name
            - Manager
          subtext:
            - key: job_description
            - Description of position
        value:
          _type: Manager
          name:
          job_description:
          profile_picture:
          url:
staff:
  - _type: Employee
    name: Billy Mills
    job_description: Billy is our Marketing Associate!
    profile_picture: /images/team/1.jpg
  - _type: Manager
    name: Karen Key
    job_description: Karen is our Regional Coordinator!
    profile_picture: /images/team/4.jpg
    url:
  - _type: Employee
    name:
    job_description:
    profile_picture:
  - _type: Manager
    name:
    job_description:
    profile_picture:
    url:
---
