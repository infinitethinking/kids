# kids

Weekly training planner: https://infinitethinking.github.io/kids/

Clicks on O/L, edits, and extra sessions are stored in [`planner-data.json`](planner-data.json) in this repository. They are **not** kept until you click **Enregistrer**.

## Save from the planner

1. Open [fine-grained personal access tokens](https://github.com/settings/personal-access-tokens/new).
2. Token name: `kids planner`.
3. Resource owner: `infinitethinking`.
4. Repository access: only **kids**.
5. Repository permissions: **Contents** → **Read and write**.
6. Generate the token and paste it once in the planner. It stays in that browser (local storage), not in the page source.
7. Click **Enregistrer**. Other devices see the same plan after a reload (data is read from GitHub, not from the Pages cache).

Anyone with the token can write to this repo. Use **Oublier le jeton** on a shared computer.
