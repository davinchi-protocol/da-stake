# Davinchi Staking Deposit Validator

##### Python version checking

Ensure you are using Python version >= Python3.8:

```sh
sudo apt install python3-pip
```

##### Step 1. Installation

Install the dependencies:

```sh
pip3 install -r requirements.txt
python3 setup.py install
```

Or use the helper script:

```sh
./deposit.sh install
```

You can also run the tool with optional arguments:

```sh
./deposit.sh new-mnemonic --num_validators=<NUM_VALIDATORS> --mnemonic_language=english --chain=<CHAIN_NAME> --folder=<YOUR_FOLDER_PATH>
```

```sh
./deposit.sh existing-mnemonic --num_validators=<NUM_VALIDATORS> --validator_start_index=<START_INDEX> --chain=<CHAIN_NAME> --folder=<YOUR_FOLDER_PATH>
```