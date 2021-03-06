## bq78350-R1
- ManufacturerAccess
- RemainingCapacityAlarm
- RemainingTimeAlarm
- BatteryMode
- BatteryMode
- AtRate
- AtRateTimeToFull
- AtRateTimeToEmpty
- AtRateOK
- Temperature
- Voltage
- Current
- AverageCurrent
- MaxError
- RelativeStateOfCharge
- AbsoluteStateOfCharge
- RemainingCapacity
- FullChargeCapacity
- RunTimeToEmpty
- AverageTimeToEmpty
- AverageTimeToFull
- ChargingCurrent
- ChargingVoltage
- BatteryStatus
- CycleCount
- DesignCapacity
- DesignVoltage
- SpecificationInfo
- ManufacturerDate
- SerialNumber
- ManufacturerName
- DeviceName
- DeviceChemistry
- ManufacturerData
- HostFETControl
- GPIOStatus
- GPIOControl
- VAUXVoltage
- Authenticate
- CellVoltage15 ... CellVoltage1
- DynamicPower
- ExtAveCellVoltage
- PendingEDV
- StateOfHealth
- SafetyAlert
- SafetyStatus
- PFAlert
- PFStatus
- OperationStatus
- ChargingStatus
- GaugingStatus
- ManufacturingStatus
- AFEStatus
- AFEConfig
- AFEVCx
- AFEData
- Lifetime Data Block 1 ... Lifetime Data Block 7
- ManufacturerInfo
- DAStatus 1
- DAStatus 2
- CUV Snapshot
- COV Snapshot

## bq34z100-G1
- Control()
- StateOfCharge()
- MaxError()
- RemainingCapacity()
- FullChargeCapacity()
- Voltage()
- AverageCurrent()
- Temperature()
- Flags()
- Current()
- FlagsB()

Extended Commands
- AverageTimeToEmpty()
- AverageTimeToFull()
- PassedCharge()
- DoD0Time()
- AvailableEnergy()
- AveragePower()
- Serial Number
- Internal_Temperature()
- CycleCount() - number of cycles the battery has
experienced
- StateOfHealth() - the ratio of predicted FCC (25°C, SOH current rate) over the DesignCapacity()
- ChargeVoltage() - recommended charging voltage output from the JEITA charging profile
- ChargeCurrent() - recommended charging current output from the JEITA charging profile
- PackConfiguration()
- DesignCapacity()
- DataFlashClass() (2)
- DataFlashBlock() (2)
- Authenticate()/BlockData()
- AuthenticateCheckSum()/BlockData()
- BlockData()
- BlockDataCheckSum()
- BlockDataControl()
- GridNumber()
- LearnedStatus()
- DoD@EoC() - depth of discharge (DOD) at the end of charge
- QStart() - initial capacity calculated from IT simulation
- TrueRC() - True remaining capacity from IT simulation
- TrueFCC() - True full charge capacity from IT simulation
- StateTime() - time past since last state change (DISCHARGE, CHARGE, REST)
- QMaxPassedQ
- DOD0()
- QmaxDOD0()
- QmaxTime()

## bq76930
- SYS_STAT
- CELLBAL1 CELLBAL2 - Enable individual cells for balancing
- SYS_CTRL1
- SYS_CTRL2 - Discharge and Charge FET control
- PROTECT1
- PROTECT2
- PROTECT3
- OV_TRIP
- UV_TRIP
- CC_CFG
- VC1_HI VC1_LO
- BAT_HI BAT_LO
- TS1_HI TS1_LO
- TS2_HI TS2_LO
- CC_HI CC_LO
- ADCGAIN1
- ADCOFFSET
- ADCGAIN2



