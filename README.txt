• Current Comparison (honest, as of repo now)

  +-----------------------------------------+-----------------------------+----------------+----------------+------------------+------------------------------------------
  ----+
  | Area                                    | Kaede (current)             | OpenClaw       | OpenPoke       | Winner           | Reality Check
  |
  ----+
  | Core orchestration architecture          | Hybrid (Kaede + OpenPoke)   | Medium         | Strong         | Kaede ~= OpenPoke| Kaede now has strong orchestration base.
  |
  | Sub-agent architecture depth             | Strong, but not maxed       | Medium         | Strong         | Tie (near)       | Still room to improve planner/reviewer
  |
  | Cron control plane (CLI/TCP introspect)  | Present                     | Basic          | Basic          | Kaede            | Kaede has better ops control now.
  |
  | Heartbeat/proactive reliability          | Improved, near-production   | Good           | Good           | Kaede            | Much better than before; still tune
  cadence.  |
  | Chat persistence durability              | Strong (atomic SQLite store)| Basic          | Medium         | Kaede            | Reload+append+compaction now in place.
  |
  | Memory stack breadth                     | Very strong (Fluxus+thought)| Medium         | Medium         | Kaede            | Most complete memory model of the 3.
  |
  | Tooling breadth (Discord+Composio+Molt) | Very high                   | Low            | Medium         | Kaede            | Kaede has widest usable capability
  surface.   |
  | Tool schema robustness (Gemini strict)   | Improved, still sensitive   | N/A/Lower load | N/A/Lower load | Kaede (practical)| Large tool surfaces still need strict
  hygiene.|
  | Logging architecture                     | Strong split logs, no trunc | Medium         | Medium         | Kaede            | Cleaner and more debuggable now.
  |
  | Time awareness (human-style context)     | Added (PST/date/year)       | Basic          | Basic          | Kaede            | Now explicit in AI prompt context.
  |
  | Production shard readiness               | AutoSharded                 | Basic          | Basic          | Kaede            | Better Discord scaling posture.
  |
  +-----------------------------------------+-----------------------------+----------------+----------------+------------------+------------------------------------------
  ----+
