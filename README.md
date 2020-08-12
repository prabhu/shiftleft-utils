# ShiftLeft Utils

Collection of scripts to help integrate ShiftLeft NextGen Analysis with your DevOps workflow.

## Usage

Install python 3 on the machine or vm running the scripts.

Clone the repo.

```bash
cd shiftleft-utils
pip install -r requirements.txt
```

Set the ShiftLeft Org Id, access token and api token as following environment variables.

- SHIFTLEFT_ORG_ID
- SHIFTLEFT_ACCESS_TOKEN

## Description of scripts

| Script    | Purpose                                               |
| --------- | ----------------------------------------------------- |
| export.py | Export NG SAST findings report to xml and json format |

## License

Apache-2.0
