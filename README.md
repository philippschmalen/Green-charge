# Green stickkontakt

## Data

###

### Target (y)

> The target definition has to ensure 1. battery fully charged (~> 4h), 2. highest green energy share within charging window

Different definitions for y are possible:

1. Absolute: 4 hours within from 6pm - 6am with the highest green energy share
2. Relative to time of demand: After plugging in, set the time when you need your device back. For example, you plug in at 6pm and need it back at 7am. The model finds the optimal charging window within that time. Otherwise assume a default of 8 hours

---

## Get started (devs)

Run the following in the project root `./`:

```bash
# create and activate conda env
conda env create -f conda.yaml -y
conda activate chargegreen

# init pre-commit
pre-commit install
pre-commit autoupdate
```

---


## Extensions

* When do people charge their devices?
* What behavior patterns exist to segment the day?

---

## Product ideas

* USB C charging station
