# view current README conflict to decide what to keep
cat README.md

# Example quick replace (customize the content to what you want)
cat > README.md <<'EOF'
# Time Travel Zine (time-travel-asachd22)

Short project description: I am exploring Git workflows and building a small zine — using Git as a "time machine".

Branches:
- author/idea-sprint — used for draft content and ideas.
- editor/review — used for editorial fixes and polishing.

(You can expand this as needed.)
EOF

