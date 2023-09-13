# gpmfactory APEX tools
Gmfactory repository
Miscellaneous tools.

1. Generates a code snippet for a popup lov item
 generates the "Initialization JavaScript Function" attribute
 for a popup lov item in an Oracle APEX application
 GPM Factory sep 2023 - V1

Install:
import and run  gen_initjs.sql script
Optionnaly: import rest module from ORDS_REST_DEMO_ujs_2023_09_13.sql

Usage:
either from sql editor as:
  select gen_initjs(162,'USER_TABLES') from dual
or by calling the rest module as:
  https://xxxxxxxx.oraclecloudapps.com/ords/demo/ujs/lov/<APPLICATION_ID>/<LOV_NAME>
