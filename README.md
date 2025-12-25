# KlippyResonanceGraphs
Example project to generate graphs from Klipper test resonances in the external daemon

# Testing

```
git clone https://github.com/nefelim4ag/KlippyResonanceGraphs.git
cd KlippyResonanceGraphs
./install.sh
# Run
.venv/bin/python3 ./graph-gen-service.py
```
Now you can call `EXTERNAL_TEST_RESONANCES`, which executes everything from the external process.

There is no systemd service on purpose.
It is not supposed for the end user.
