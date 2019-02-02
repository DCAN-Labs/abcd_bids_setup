# ABCD TGZ to BIDS Input Setup

`unpack_and_setup.sh` does the work.  It takes three arguments:

```
SUB=$1 # Full BIDS formatted subject ID (sub-SUBJECTID)
VISIT=$2 # Full BIDS formatted session ID (ses-SESSIONID)
TGZDIR=$3 # Path to directory containing all .tgz for subject
```

**IMPORTANT**: update paths inside the script everywhere a `...` appears.
