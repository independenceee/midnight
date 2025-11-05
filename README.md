```
sudo apt update
sudo apt install tmux -y
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
curl -LsSf https://astral.sh/uv/install.sh | sh
source ~/bashrc
```

```
cd ce-ashmaize/cli_hunt/rust_solver
cargo build --release
cd .. # Go back to the cli_hunt dir
touch python_orchestrator/challenges.json
```

```
cd python_orchestrator  
uv run main.py run
```
