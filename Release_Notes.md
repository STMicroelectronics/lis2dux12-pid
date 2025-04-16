---
pagetitle: Release Notes for LIS2DUX12 Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LIS2DUX12 Component Driver
Copyright &copy; 2022 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LIS2DUX12 component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 14-November-2022</label>
<div>

## Main changes

### First release

- First official release [ref. DS v2.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V1.0.1 / 07-April-2023</label>
<div>

## Main changes
- fix defines for low power ODRs
- Fix BW setting for LP mode with ODR < 50 Hz


##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V1.1.0 / 01-June-2023</label>
<div>

## Main changes
- lis2dux12_reg.c(h): Fix struct and enum names

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V1.1.1 / 21-June-2023</label>
<div>

## Main changes
- Fix a typo in pin_int2_route_set

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V1.1.2 / 28-June-2023</label>
<div>

## Main changes
- Fix typos in ODR define names

##

</div>

<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V1.1.3 / 24-July-2023</label>
<div>

## Main changes
- Add APIs to set/get FSM/MLC fifo_en bit

##

</div>

<input type="checkbox" id="collapse-section7" aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V1.1.4 / 27-July-2023</label>
<div>

## Main changes
- moved all enum outside of struct to be C++ compliant

##

</div>

<input type="checkbox" id="collapse-section8" aria-hidden="true">
<label for="collapse-section8" aria-hidden="true">V1.2.0 / 27-Nov-2023</label>
<div>

## Main changes
- Align driver to DS v3.0
- Add wait BOOT/RESET/Power-Down as specified in AN5909

##

</div>

<input type="checkbox" id="collapse-section9" aria-hidden="true">
<label for="collapse-section9" aria-hidden="true">V2.0.0 / 20-Mar-2024</label>
<div>

## Main changes
- Fixed code style (Artistic Style Version 3.4.13)
- Add "const" to ctx arg for all APIs

##

</div>

<input type="checkbox" id="collapse-section10" aria-hidden="true">
<label for="collapse-section10" aria-hidden="true">V2.0.1 / 26-Mar-2024</label>
<div>

## Main changes
- updated README.md file with tag reference and mdelay description

##

</div>

<input type="checkbox" id="collapse-section11" aria-hidden="true">
<label for="collapse-section11" aria-hidden="true">V2.0.2 / 11-Apr-2024</label>
<div>

## Main changes
- Fix lis2dux12_mode_get API

##

</div>

<input type="checkbox" id="collapse-section12" aria-hidden="true">
<label for="collapse-section12" aria-hidden="true">V2.1.0 / 22-Apr-2024</label>
<div>

## Main changes
- Aligned to DS Rev4

##

</div>

<input type="checkbox" id="collapse-section13" aria-hidden="true">
<label for="collapse-section13" aria-hidden="true">V2.2.0 / 17-May-2024</label>
<div>

## Main changes
- fix some MISRA errors found with coverity

##

</div>

<input type="checkbox" id="collapse-section14" aria-hidden="true">
<label for="collapse-section14" aria-hidden="true">V2.2.1 / 25-Sept-2024</label>
<div>

## Main changes
- Fix multiple byte read in ln_pg_read() API
- (FIX) Return 6Hz_HP or 6_Hz_LP in mode_get API
- Fix BW setting in mode_set API
- Fix FIFO data get API
- Fixed few typos

##

</div>

<input type="checkbox" id="collapse-section15" aria-hidden="true">
<label for="collapse-section15" aria-hidden="true">V2.3.0 / 18-Dec-2024</label>
<div>

## Main changes

- revert fifo change according to review
- Fix reading fifo register
- Add smart_power configuration

##

</div>

<input type="checkbox" id="collapse-section16" aria-hidden="true">
<label for="collapse-section16" aria-hidden="true">V2.4.0 / 07-Apr-2025</label>
<div>

## Main changes

- Aligned to DS rev7
- fix RESET case in init_set()
- Add fifo_event_t enum to set stop_on_fth bit
- Use defines (and not numbers) as FIFO tags

##

</div>

<input type="checkbox" id="collapse-section17" checked aria-hidden="true">
<label for="collapse-section17" aria-hidden="true">V2.4.1 / 16-Apr-2025</label>
<div>

## Main changes

- Fix fifo_mode_set

##

</div>
:::



:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LIS2DUX12,
visit:
[LIS2DUX12](https://www.st.com/resource/en/datasheet/lis2dux12.pdf)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
