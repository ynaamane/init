PS3='Hello Sir, choose your color ;)'
options=("France" "White to Black" "Rainbow" "I don't care about your script")
select opt in "${options[@]}"
do
    case $opt in
        "France")
			clear
			echo "\x1b[34m$(cat test)" # Bleu / Blue
			sleep 0.4
			clear
			echo "\x1b[97m$(cat test)" # Blanc / White
			sleep 0.4
			clear
			echo "\x1b[31m$(cat test)" # Rouge / Red
			sleep 0.4
			clear
			echo "\x1b[4m$(cat test)"
			echo "\x1b[97m"
			echo "\x1b[24m"
			;;
		"White to Black")
			clear
			echo "\x1b[97m$(cat test)"
			sleep 0.4
			clear
			echo "\x1b[37m$(cat test)"
			sleep 0.4
			clear
			echo "\x1b[90m$(cat test)"
			sleep 0.4
			clear
			echo "\x1b[30m$(cat test)"
			sleep 0.4
			clear
			echo "\x1b[97m"
			;;
		"Rainbow")
			clear
			echo "\x1b[31m$(cat test)" # Rouge / Red
			sleep 0.2
			clear
			echo "\x1b[91m$(cat test)" # Rouge Clair / Light Red
			sleep 0.2
			clear
			echo "\x1b[33m$(cat test)" # Jaune / Yellow
			sleep 0.2
			clear
			echo "\x1b[93m$(cat test)" # Jaune Clair / Light Yellow
			sleep 0.2
			clear
			echo "\x1b[92m$(cat test)" # Vert Clair / Light Green
			sleep 0.2
			clear
			echo "\x1b[32m$(cat test)" # Vert / Green
			sleep 0.2
			clear
			echo "\x1b[96m$(cat test)" # Light Cyan
			sleep 0.2
			clear
			echo "\x1b[36m$(cat test)" # Cyan
			sleep 0.2
			clear
			echo "\x1b[94m$(cat test)" # Bleu Clair / Light Blue
			sleep 0.2
			clear
			echo "\x1b[34m$(cat test)" # Bleu / Blue
			sleep 0.2
			clear
			echo "\x1b[35m$(cat test)" # Mauve / Magenta
			sleep 0.2
			clear
			echo "\x1b[95m$(cat test)" # Mauve Claire / Light Magenta
			sleep 0.2
			clear
			echo "\x1b[4m$(cat test)"
			echo "\x1b[97m"
			echo "\x1b[24m"
			;;
		"I don't care about your script")
			echo "\x1b[31mMe \x1b[94mtoo \x1b[92mabout \x1b[96myou \x1b[95m!"
			break
			;;
		*) echo "invalid option $REPLY";;
	esac
done
