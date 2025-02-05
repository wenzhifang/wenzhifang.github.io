---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "2rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
  - block: collection
    id: papers
    content:
      title: Slected Works
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: compact
  - block: markdown
    id: news
    content:
      title: News
      subtitle: ''
      text: |-
        I am looking for an internship for 2025 summer.
#       - Nov 2024: One paper has been accepted to [IEEE Journal of Selected Areas in Sensors](https://ieee-jsas.org/).
    design:
      columns: '1'
  - block: markdown
    id: service
    content:
      title: Academic Services
      subtitle: ''
      text: |-
        ### Conference Reviewer
        - [Advances in Neural Information Processing Systems (NeurIPS)](https://neurips.cc/)
        - [International Conference on Machine Learning (ICML)](https://icml.cc/)
        - [International Conference on Learning Representations (ICLR)](https://iclr.cc/Conferences/2025)
        - [International Conference on Artificial Intelligence and Statistics (AISTATS)](https://aistats.org/aistats2025/)
        - [IEEE International Conference on Computer Communications (INFOCOM)](https://infocom2024.ieee-infocom.org/)
        ### Journal Reviewer
        - [Transactions on Machine Learning Research (TMLR)](https://jmlr.org/tmlr/)
        - [IEEE Transactions on Wireless Communications (TWC)](https://www.comsoc.org/publications/journals/ieee-twc)
        - [IEEE Transactions on Communications (TCOM)](https://www.comsoc.org/publications/journals/ieee-tcom)
        - [IEEE Transactions on Mobile Computing (TMC)](https://www.computer.org/csdl/journal/tm)
        - [IEEE Internet of Things Journal (IoT-J)](https://ieee-iotj.org/)
        - [IEEE Transactions on Machine Learning in Communications and Networking (TMLCN)](https://www.comsoc.org/publications/journals/ieee-tmlcn)
    design:
      columns: '1'
  # - block: contact
  #   id: contact
  #   content:
  #     # Optional front matter you can reference in contact.html
  #     title: "Contact"
  #     text: "Reach out via email or come visit!"
---
