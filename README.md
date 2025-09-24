# SAP-ABAP_Classic-Report.
Classic Report - Write Statement
REPORT ZPRACTICEVG01.

DATA :lv_sub TYPE char20.

PARAMETER : P_first TYPE char10,
            p_second TYPE char10.

lv_sub = p_first - p_second.

write: 'subtraction of p_first and p_second is', lv_sub.
