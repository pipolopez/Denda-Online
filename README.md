# Denda-Online
Plantilla
mkdir -p .claude-plugin
cat > .claude-plugin/plugin.json <<'EOF'
{
  "name": "denda-online",
  "version": "0.1.0",
  "description": "Descripción breve del plugin"
}
EOF
git add .claude-plugin/plugin.json
git commit -m "Añadir plugin.json"
git push
