# evm-tools
Collection of tools to interact with EVM compatible blockchains.<p>
You will need to add the path to the evm-tools directory you cloned to your PYTHONPATH env var for all imports to work as intended.
<pre>
 export PYTHONPATH="${PYTHONPATH}:/path/to/evm-tools"
</pre>

## token-sniffer
Listen for PairCreated events and notify of pair and tx hash via discord webhook.
<pre>
 Usage: ./token-sniffer.py run --config /path/to/config.json
</pre>
