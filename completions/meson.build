zsh_install_dir = join_paths(get_option('datadir'), 'zsh', 'site-functions')
fish_install_dir = join_paths(get_option('datadir'), 'fish', 'vendor_completions.d')
bash_install_dir = join_paths(get_option('datadir'), 'bash-completion', 'completions')
install_data('zsh/_hyprctl', install_dir: zsh_install_dir)
install_data('fish/hyprctl.fish', install_dir: fish_install_dir)
install_data('bash/hyprctl', install_dir: bash_install_dir)
