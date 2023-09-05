# Modified Steps for Ubuntu 22.04 LTS

## Clone Repo

```bash
git clone git@github.com:ledger/ledger.git
cd ledger && ./acprep update
```

## Install Dependencies

```bash
./acprep dependencies
```

## Building

```bash
./acprep update
make check # To confirm
make install
```

## You did it!
Now try your first ledger command:

```bash
ledger -f test/input/sample.dat reg
```