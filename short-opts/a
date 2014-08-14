#!/usr/bin/env bash
set -eo pipefail; [[ -n "$PLUSHU_TRACE" ]] && set -x

case "$1" in
  -a=*)
    export PLUSHU_APP_NAME=${1#-a=}
    shift
    ;;

  -a)
    shift
    export PLUSHU_APP_NAME=$1
    shift
    ;;

  -a*)
    export PLUSHU_APP_NAME=${1#-a}
    shift
    ;;
esac
