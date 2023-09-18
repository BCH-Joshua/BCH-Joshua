name: BCH-Joshua
run-name: ${{ github.actor }} is testing out GitHub Actions 🚀
on: [push]
jobs:
  Explore-GitHub-Actions:
    runs-on: ubuntu-latest
    steps:
      - run: echo "👋 Hi, I’m @BCH-Joshua."
      - run: echo "👀 I’m interested in"
      - run: echo "🌱 I’m currently learning."
      - name: Check out repository code
        uses: actions/checkout@v3
      - run: echo "💞️ I’m looking to collaborate on."
      - run: echo "📫 How to reach me."
      - name: List files in the repository
        run: |
          ls ${{ github.workspace }}
      - run: echo "🍏 This job's status is ${{ job.status }}."
