# forge-script-setup-bug

Running the following command fails
```bash
forge script CounterScript
```

Commenting out line 8 (the empty setup function) of `Counter.s.sol` makes the above command work.

Expected behaviour is that the empty setup function doesn't cause any issues.
