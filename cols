#!/usr/bin/env bash

MAIN_(){
  local COLR=16
  for COLR in {0..255}; do
    echo -e "\\033[38;5;${COLR}m\\033[48;5;${COLR}mAAAA\\033[0m - \\\033[38;5;$COLR\0m"
    ((COLR++))
  done
}
MAIN_
