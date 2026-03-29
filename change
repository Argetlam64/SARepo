PY="run.py"
SH="run.sh"
PY_BASE="run_python"
SH_BASE="run_shell"

rm $PY
rm $SH

if [[ $1 == "py" ]]; then
	cp $PY_BASE $PY
fi;

if [[ $1 == "sh" ]]; then
	cp $SH_BASE $SH
fi;

./push
