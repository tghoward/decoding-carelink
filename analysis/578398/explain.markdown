# ./status-quo.sh /dev/ttyUSB0 578398
## cat ./status-quo.sh
```bash
```
## cat logs/explain.log
OUT
## Observations
Wed Apr 29 20:16:48 PDT 2015

## stick

* stick runs appear to be ok

## pump


## downloaded: 11

```
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][0]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][10]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][1]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][2]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][3]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][4]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][5]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][6]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][7]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][8]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][9]:data[1024]:
```


## commands session:finished: 23

```
INFO:session:finished executing:ReadBasalTemp:size[64]:data:{'duration': 0, 'rate': 1.3}
INFO:session:finished executing:ReadBatteryStatus:size[64]:data:{'status': 'normal', 'voltage': 1.19}
INFO:session:finished executing:ReadContrast:size[64]:data:bytearray(b'\x02\x07\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00\x00')
INFO:session:finished executing:ReadCurPageNumber:pages:10
INFO:session:finished executing:ReadFirmwareVersion:size[64]:data:'VER 2.4A1.1'
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][0]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][10]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][1]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][2]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][3]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][4]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][5]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][6]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][7]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][8]:data[1024]:
INFO:session:finished executing:ReadHistoryData:size[1024]:[page][9]:data[1024]:
INFO:session:finished executing:ReadPumpID:size[64]:data:'578398'
INFO:session:finished executing:ReadPumpModel:size[64]:data:'522'
INFO:session:finished executing:ReadRadioCtrlACL:size[64]:data:['------', '------', '------']
INFO:session:finished executing:ReadRemainingInsulin:size[64]:data:35.5
INFO:session:finished executing:ReadRTC:size[64]:data:'2015-4-29T20:14:58'
INFO:session:finished executing:ReadSettings:size[64]:data:{'low_reservoir_warn_point': 20, 'keypad_lock_status': 0, 'maxBasal': 2, 'temp_basal': {'percent': 100, 'type': 'Units/hour'}, 'paradigm_enabled': 1, 'insulinConcentration': 100, 'audio_bolus_enable': False, 'variable_bolus_enable': True, 'alarm': {'volume': -1, 'mode': 1}, 'rf_enable': False, 'block_enable': False, 'timeformat': 0, 'auto_off_duration_hrs': 0, 'audio_bolus_size': 0, 'selected_pattern': 0, 'patterns_enabled': False, 'insulin_action_type': 4, 'maxBolus': 15.0, 'low_reservoir_warn_type': 0}
INFO:session:finished executing:ReadTotalsToday:size[64]:data:{'yesterday': 57.3, 'today': 43.2}
```

## howdy! pump runs appear to be OK

* NO CRC ERROR FOUND
* no nak found
* SUCCESS, GOOD CLEAN RUN
