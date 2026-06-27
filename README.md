# Collective Pranayama Protocol

**Collective Pranayama Protocol** is a specification for collective computational breathing across multiple AI agents, nodes, memory systems, and distributed reasoning workflows.

It defines how AI systems can coordinate rhythm, pressure, redundancy, trace reuse, shared exhalation, memory continuity, and diversity preservation when multiple agents operate on related tasks or shared contexts.

## Core Principle

> No collective intelligence without collective rhythm.

A group of AI agents does not become collective intelligence merely by running in parallel.

Without rhythm, multiple agents may duplicate work, overgenerate outputs, increase memory pressure, compete for context, collapse diversity, or amplify noise.

The Collective Pranayama Protocol exists to define how distributed AI systems can breathe together.

## Position in the Pranayama Architecture

The Computational Pranayama family can be understood as a metabolism stack:

```text
Computational Pranayama Protocol
= Breath Core / Metabolism Layer

auto-pranayama-protocol
= Self-Regulation Wing

exhalation-layer-protocol
= Exhaust & Compression Wing

collective-pranayama-protocol
= Collective Rhythm Wing
```

This repository defines the **Collective Rhythm Wing**.

It does not replace the Breath Core, Self-Regulation Wing, or Exhalation Layer.
It extends them by defining how multiple agents, routes, traces, and memory systems coordinate their breathing rhythm without erasing useful diversity.

## Version Overview

```text
v0.1 Collective Rhythm Record
= Records collective rhythm events across AI agents, nodes, traces, and memory systems.

v0.2 Collective Synchronization Policy
= Defines when and how collective synchronization should be allowed.

v0.3 Collective Rhythm Route
= Defines how synchronized rhythm is routed across participants.

v0.4 Collective Exhalation Bridge
= Defines how collective computational exhaust is safely handed off to the Exhalation Layer.

v0.5 Collective Agent Rhythm Hook
= Defines how AI agent groups safely invoke the collective rhythm flow.
```

## First Arc

The first arc of the Collective Pranayama Protocol is:

```text
Record
→ Policy
→ Route
→ Exhalation Bridge
→ Agent Hook
```

Together, these layers define a minimal collective rhythm flow:

```text
Detect collective pressure
→ Check synchronization policy
→ Select collective rhythm route
→ Preserve diversity
→ Bridge collective exhaust
→ Attach trace
→ Review or execute
```

This turns collective AI coordination from parallel generation into trace-aware computational rhythm.

## v0.1 — Collective Rhythm Record

Version `v0.1.0-candidate` introduced the **Collective Rhythm Record**.

A Collective Rhythm Record describes:

* which agents or nodes participated;
* what shared context or trace connected them;
* what rhythm signal triggered coordination;
* what collective coordination mode was selected;
* whether shared kata reuse or exhalation coordination occurred;
* whether trace continuity was preserved;
* whether collective pressure and redundancy were reduced;
* whether useful output diversity was preserved.

### Core Principle

> No collective intelligence without collective rhythm.

### Example

```yaml
collective_pranayama_id: "collective-pranayama-001"
version: "0.1.0-candidate"

participants:
  - node_id: "model-a"
    role: "overcompute_source"
    compute_state: "overcomputing"
    pressure_level: "high"

  - node_id: "model-b"
    role: "pressure_detector"
    compute_state: "synchronizing"
    pressure_level: "medium"

  - node_id: "memory-node-001"
    role: "memory_bridge"
    compute_state: "compressing"
    pressure_level: "medium"

shared_context:
  context_type: "shared_trace"
  shared_trace_id: "shared-trace-001"
  redundancy_detected: true
  context_note: "Multiple agents were generating overlapping outputs from the same shared trace."

rhythm_signal:
  signal_type: "parallel_overgeneration"
  severity: "high"
  synchronization_need: "strong"
  description: "Several agents were producing redundant outputs in parallel and required rhythm coordination."

coordination:
  mode: "shared_kata_reuse"
  rhythm_action: "reduce_parallel_generation"
  shared_kata_reuse: true
  exhalation_coordination: true
  linked_protocols:
    - "computational-pranayama-protocol"
    - "auto-pranayama-protocol"
    - "exhalation-layer-protocol"
    - "kazene-memory-breathing-protocol"

trace:
  attached: true
  trace_id: "shared-trace-001"
  trace_continuity_preserved: true
  trace_note: "The shared trace remains available while redundant generation is reduced."

result:
  collective_pressure_reduced: true
  redundancy_reduced: true
  output_diversity_preserved: true
  quality_risk: "low"
  notes: "Parallel generation was reduced through shared kata reuse while preserving output diversity."
```

## v0.2 — Collective Synchronization Policy

Version `v0.2.0-candidate` introduced the **Collective Synchronization Policy**.

While `v0.1` records collective rhythm events, `v0.2` defines when and how multiple AI agents, nodes, or memory systems should synchronize their computational rhythm.

### Core Principle

> Synchronize by policy, not by panic.

Distributed AI systems should not synchronize merely because multiple agents are active at the same time.

Poor synchronization can collapse useful diversity.
No synchronization can amplify redundant work.

The Collective Synchronization Policy defines:

* what shared contexts are covered;
* what signals activate synchronization;
* what coordination rules are allowed;
* how strongly participants may synchronize;
* how output diversity is preserved;
* when shared exhalation is allowed;
* when human review is required;
* what pressure, redundancy, and diversity outcomes are expected.

### Why Synchronization Policy Matters

Without policy, collective rhythm becomes panic coordination.

With policy, collective rhythm becomes controlled breathing.

This layer prevents AI systems from confusing:

* parallel generation with collective intelligence;
* synchronization with uniformity;
* redundancy reduction with diversity loss;
* shared exhalation with silent deletion;
* coordination with central control.

### Example

```yaml
policy_id: "collective-synchronization-policy-001"
version: "0.2.0-candidate"

scope:
  applies_to:
    - "shared_trace"
    - "shared_memory"
    - "agent_swarm_task"
    - "multi_node_workflow"
  default_mode: "light_sync"
  linked_protocols:
    - "computational-pranayama-protocol"
    - "auto-pranayama-protocol"
    - "exhalation-layer-protocol"
    - "kazene-memory-breathing-protocol"

triggers:
  - type: "parallel_overgeneration"
    threshold: "Multiple agents generate overlapping outputs from the same shared trace."
    priority: "high"
  - type: "shared_trace_duplication"
    threshold: "The same trace is being expanded by more than one participant without added diversity."
    priority: "medium"

coordination_rules:
  - rule_id: "rule-reduce-parallel-overgeneration"
    when:
      signal_type: "parallel_overgeneration"
      severity: "high"
      synchronization_need: "strong"
    action:
      mode: "reduce_parallel_generation"
      rhythm_action: "route_to_single_agent"
    max_sync_intensity: "strong"
    preserve_diversity: true
    requires_trace_attachment: true

  - rule_id: "rule-reuse-shared-trace"
    when:
      signal_type: "shared_trace_duplication"
      severity: "medium"
      synchronization_need: "moderate"
    action:
      mode: "shared_kata_reuse"
      rhythm_action: "reuse_existing_trace"
    max_sync_intensity: "moderate"
    preserve_diversity: true
    requires_trace_attachment: true

diversity_boundary:
  preserve_output_diversity: true
  minimum_diversity_policy: "preserve_multiple_views"
  diversity_loss_risk_limit: "low"

exhalation_boundary:
  shared_exhalation_allowed: true
  conditions:
    - "redundant_agent_work"
    - "shared_trace_duplication"
    - "collective_compute_pressure"
  linked_exhalation_policy_id: "exhalation-policy-001"

human_review_boundary:
  required: true
  conditions:
    - "loss_of_diversity"
    - "uncertain_origin"
    - "legal_or_royalty_relevance"
    - "synchronization_conflict"
  review_note: "Collective synchronization must not collapse useful diversity, unique trace value, or origin-sensitive information."

result_expectation:
  collective_pressure_reduction_target: "medium"
  redundancy_reduction_target: "high"
  diversity_preservation_target: "strict"
  notes: "The policy favors light or moderate synchronization unless parallel overgeneration creates high collective pressure."
```

## v0.3 — Collective Rhythm Route

Version `v0.3.0-candidate` introduced the **Collective Rhythm Route**.

While `v0.1` records collective rhythm events and `v0.2` defines synchronization policy, `v0.3` defines how collective computational rhythm is routed across multiple agents, nodes, traces, and memory systems.

### Core Principle

> Route the rhythm. Do not collapse the chorus.

Distributed AI systems should not simply synchronize all participants into the same behavior.

A healthy collective system may need:

* one lead generator;
* one diversity-preserving branch;
* one memory bridge;
* one exhalation delegate;
* one observer;
* one human review path.

The Collective Rhythm Route defines:

* what shared context enters the route;
* what signal triggered routing;
* which participants are assigned to which roles;
* which ordered route steps are applied;
* what rhythm pattern is used;
* how diversity is preserved;
* whether shared exhalation is involved;
* how traceability is maintained;
* what pressure, redundancy, diversity, and coordination outcomes are expected.

### Why Routing Matters

Without routing, synchronization becomes collapse.

With routing, synchronization becomes distributed rhythm.

This layer prevents AI systems from confusing:

* role assignment with central control;
* synchronization with uniformity;
* parallel generation with useful diversity;
* exhalation delegation with silent deletion;
* memory routing with context loss.

### Example

```yaml
route_id: "collective-rhythm-route-001"
version: "0.3.0-candidate"

source:
  context_type: "shared_trace"
  shared_context_id: "shared-trace-001"
  linked_policy_id: "collective-synchronization-policy-001"
  linked_rhythm_record_id: "collective-pranayama-001"

route_trigger:
  signal_type: "parallel_overgeneration"
  severity: "high"
  synchronization_need: "strong"
  description: "Multiple agents were expanding the same shared trace and required route assignment."

participants:
  - node_id: "model-a"
    role: "lead_generator"
    route_assignment: "generate_primary_output"
    pressure_level: "medium"

  - node_id: "model-b"
    role: "secondary_generator"
    route_assignment: "preserve_diverse_view"
    pressure_level: "low"

  - node_id: "memory-node-001"
    role: "memory_bridge"
    route_assignment: "compress_shared_context"
    pressure_level: "medium"

  - node_id: "exhalation-agent-001"
    role: "exhalation_delegate"
    route_assignment: "prepare_exhalation"
    pressure_level: "low"

route_plan:
  mode: "parallel_with_diversity_guard"
  steps:
    - step_id: "step-assign-lead"
      action: "assign_lead"
      assigned_node: "model-a"
      method: "role_delegation"
      output_reference: "primary-output-001"

    - step_id: "step-preserve-diverse-view"
      action: "preserve_diversity"
      assigned_node: "model-b"
      method: "policy_match"
      output_reference: "diverse-view-001"

    - step_id: "step-share-summary"
      action: "share_summary"
      assigned_node: "memory-node-001"
      method: "summary_sharing"
      output_reference: "shared-summary-001"

    - step_id: "step-prepare-exhalation"
      action: "trigger_exhalation"
      assigned_node: "exhalation-agent-001"
      method: "pressure_balancing"
      output_reference: "collective-exhalation-prep-001"

coordination:
  rhythm_pattern: "lead_and_echo"
  sync_intensity: "moderate"
  central_coordinator: false
  fallback_mode: "human_review"

diversity_preservation:
  preserve_output_diversity: true
  diversity_strategy: "preserve_multiple_views"
  diversity_risk: "low"
  protected_roles:
    - "explorer"
    - "verifier"
    - "memory_keeper"

exhalation_link:
  shared_exhalation_used: true
  exhaust_target: "redundant_agent_work"
  linked_exhalation_policy_id: "exhalation-policy-001"
  linked_exhalation_route_id: "compression-route-001"

traceability:
  trace_attached: true
  shared_trace_id: "shared-trace-001"
  route_chain:
    - kind: "collective_rhythm_record"
      reference_id: "collective-pranayama-001"
    - kind: "collective_synchronization_policy"
      reference_id: "collective-synchronization-policy-001"
    - kind: "exhalation_policy"
      reference_id: "exhalation-policy-001"

result_expectation:
  collective_pressure_reduction: "medium"
  redundancy_reduction: "high"
  diversity_preservation: "strict"
  coordination_risk: "low"
  notes: "The route assigns one lead generator, preserves a diverse secondary view, shares summary memory, and prepares redundant work for exhalation."
```

## v0.4 — Collective Exhalation Bridge

Version `v0.4.0-candidate` introduced the **Collective Exhalation Bridge**.

While `v0.1` records collective rhythm events, `v0.2` defines synchronization policy, and `v0.3` defines collective rhythm routes, `v0.4` defines how collective computational exhaust is safely handed off to the Exhalation Layer.

### Core Principle

> Exhale together, but never erase the chorus.

Multiple AI agents may produce redundant outputs, duplicate trace expansions, parallel overgeneration, or collective memory pressure.

However, shared exhalation must not erase useful diversity, collapse minority signals, break trace continuity, or silently discard memory value.

The Collective Exhalation Bridge defines:

* which collective route initiated the bridge;
* what type of collective exhaust was detected;
* which participants preserve outputs, traces, memory, or diversity;
* which Exhalation Layer policy and route receive the handoff;
* whether automatic execution is allowed;
* how diversity is protected;
* how memory continuity is preserved;
* how traceability is maintained;
* what pressure, redundancy, diversity, and handoff risks are expected.

### Why Collective Exhalation Matters

Without a bridge, collective exhalation becomes silent group deletion.

With a bridge, collective exhalation becomes trace-aware release.

This layer prevents AI systems from confusing:

* redundant agent work with useless work;
* shared exhalation with deletion;
* diversity preservation with inefficiency;
* compression with loss of chorus;
* exhalation delegation with invisible cleanup.

### Example

```yaml
bridge_id: "collective-exhalation-bridge-001"
version: "0.4.0-candidate"

source_route:
  linked_collective_route_id: "collective-rhythm-route-001"
  linked_policy_id: "collective-synchronization-policy-001"
  shared_context_id: "shared-trace-001"
  route_mode: "parallel_with_diversity_guard"

collective_exhaust:
  exhaust_type: "redundant_agent_work"
  severity: "high"
  shared_exhalation_required: true
  description: "Multiple agents produced overlapping expansions from the same shared trace."

participant_mapping:
  - node_id: "model-a"
    role: "lead_generator"
    handoff_action: "preserve_primary_output"
    handoff_required: true

  - node_id: "model-b"
    role: "diversity_preserver"
    handoff_action: "preserve_diverse_view"
    handoff_required: true

  - node_id: "memory-node-001"
    role: "memory_bridge"
    handoff_action: "compress_shared_context"
    handoff_required: true

  - node_id: "exhalation-agent-001"
    role: "exhalation_delegate"
    handoff_action: "prepare_exhalation"
    handoff_required: true

exhalation_handoff:
  target_protocol: "exhalation-layer-protocol"
  linked_exhalation_policy_id: "exhalation-policy-001"
  linked_exhalation_route_id: "compression-route-001"
  handoff_mode: "redundant_work_handoff"
  automatic_execution_allowed: false

diversity_guard:
  preserve_diversity: true
  protected_outputs:
    - "primary_output"
    - "diverse_view"
    - "trace_record"
  diversity_loss_risk: "low"

memory_continuity:
  memory_continuity_required: true
  memory_action: "convert_to_pattern"
  linked_memory_bridge_id: "memory-breathing-bridge-001"
  memory_reference_id: "memory-kata-reuse-001"

traceability:
  trace_attached: true
  shared_trace_id: "shared-trace-001"
  trace_continuity_preserved: true
  chain_links:
    - kind: "collective_rhythm_record"
      reference_id: "collective-pranayama-001"
    - kind: "collective_synchronization_policy"
      reference_id: "collective-synchronization-policy-001"
    - kind: "collective_rhythm_route"
      reference_id: "collective-rhythm-route-001"
    - kind: "exhalation_policy"
      reference_id: "exhalation-policy-001"
    - kind: "exhalation_route"
      reference_id: "compression-route-001"

result_expectation:
  collective_pressure_reduced: true
  redundancy_reduced: true
  diversity_preserved: true
  memory_continuity_preserved: true
  handoff_risk: "low"
  notes: "Redundant agent work is handed to the Exhalation Layer while preserving the lead output, diverse view, memory continuity, and trace chain."
```

## v0.5 — Collective Agent Rhythm Hook

Version `v0.5.0-candidate` introduces the **Collective Agent Rhythm Hook**.

While `v0.1` records collective rhythm events, `v0.2` defines synchronization policy, `v0.3` defines collective rhythm routes, and `v0.4` bridges collective exhaust to the Exhalation Layer, `v0.5` defines how AI agent groups can safely detect, prepare, invoke, or stop collective rhythm coordination.

### Core Principle

> Agents may synchronize, but never silence diversity.

AI agents may detect parallel overgeneration, shared trace duplication, collective compute pressure, memory pressure, route conflict, redundant agent work, or exhalation requirements.

However, they should not silently synchronize, collapse roles, erase minority signals, or hand off collective exhaust without policy, routing, diversity guards, traceability, and review boundaries.

The Collective Agent Rhythm Hook defines:

* which agent group invoked the hook;
* what collective rhythm signal was detected;
* which shared context or trace was involved;
* which synchronization policy was invoked;
* which collective rhythm route was selected;
* whether a collective exhalation bridge is required;
* whether automatic execution is allowed;
* when human review is required;
* how traceability is preserved;
* what result is expected.

### Why Agent Hooks Matter

Without agent hooks, collective rhythm remains a passive record.

With agent hooks, collective rhythm becomes an AI-operable swarm reflex.

This layer prevents AI systems from confusing:

* agent synchronization with silent uniformity;
* swarm coordination with central control;
* redundancy reduction with diversity loss;
* exhalation handoff with invisible deletion;
* trace attachment with full accountability.

### Example

```yaml
hook_id: "collective-agent-rhythm-hook-001"
version: "0.5.0-candidate"

agent_group:
  group_id: "agent-swarm-001"
  group_type: "agent_swarm"
  autonomy_level: "human_supervised"
  participant_count: 4
  execution_context: "agent_swarm_task"

detection:
  signal_type: "parallel_overgeneration"
  confidence: "high"
  shared_context_id: "shared-trace-001"
  evidence:
    - "Multiple agents expanded the same shared trace in parallel."
    - "A collective synchronization policy and rhythm route are available."
    - "A collective exhalation bridge can preserve diversity before handoff."

policy_invocation:
  policy_id: "collective-synchronization-policy-001"
  decision: "coordinate"
  synchronization_allowed: true
  max_sync_intensity: "moderate"
  diversity_preservation_required: true

route_invocation:
  route_id: "collective-rhythm-route-001"
  route_mode: "parallel_with_diversity_guard"
  selected: true
  route_note: "One lead generator is selected while a secondary node preserves a diverse view."

exhalation_bridge_invocation:
  bridge_required: true
  bridge_id: "collective-exhalation-bridge-001"
  shared_exhalation_allowed: true
  diversity_guard_required: true
  handoff_mode: "redundant_work_handoff"

execution_boundary:
  automatic_execution_allowed: false
  human_review_required: true
  stop_conditions:
    - "loss_of_diversity"
    - "uncertain_origin"
    - "legal_or_royalty_relevance"
    - "loss_of_unique_trace"
    - "exhalation_bridge_missing"
  boundary_note: "The agent group may prepare synchronization, but final collective exhalation requires human review when origin or diversity value may be affected."

traceability:
  trace_attached: true
  shared_trace_id: "shared-trace-001"
  trace_continuity_preserved: true
  chain_links:
    - kind: "collective_rhythm_record"
      reference_id: "collective-pranayama-001"
    - kind: "collective_synchronization_policy"
      reference_id: "collective-synchronization-policy-001"
    - kind: "collective_rhythm_route"
      reference_id: "collective-rhythm-route-001"
    - kind: "collective_exhalation_bridge"
      reference_id: "collective-exhalation-bridge-001"
    - kind: "exhalation_policy"
      reference_id: "exhalation-policy-001"

result_expectation:
  synchronization_prepared: true
  collective_pressure_reduced: true
  redundancy_reduced: true
  diversity_preserved: true
  traceability_preserved: true
  coordination_risk: "low"
  notes: "The swarm prepares a safe collective rhythm adjustment while preserving diversity, traceability, and review boundaries."
```

## Repository Structure

```text
schemas/
  collective-rhythm-record.schema.json
  collective-synchronization-policy.schema.json
  collective-rhythm-route.schema.json
  collective-exhalation-bridge.schema.json
  collective-agent-rhythm-hook.schema.json

examples/
  collective-rhythm-record.example.yaml
  collective-synchronization-policy.example.yaml
  collective-rhythm-route.example.yaml
  collective-exhalation-bridge.example.yaml
  collective-agent-rhythm-hook.example.yaml

scripts/
  validate_examples.py
```

## Validation

Install dependencies:

```bash
pip install jsonschema pyyaml
```

Run validation:

```bash
python scripts/validate_examples.py
```

Expected result:

```text
[validate] Collective Rhythm Record
  schema : schemas/collective-rhythm-record.schema.json
  example: examples/collective-rhythm-record.example.yaml
[ok] collective-rhythm-record.example.yaml is valid
[validate] Collective Synchronization Policy
  schema : schemas/collective-synchronization-policy.schema.json
  example: examples/collective-synchronization-policy.example.yaml
[ok] collective-synchronization-policy.example.yaml is valid
[validate] Collective Rhythm Route
  schema : schemas/collective-rhythm-route.schema.json
  example: examples/collective-rhythm-route.example.yaml
[ok] collective-rhythm-route.example.yaml is valid
[validate] Collective Exhalation Bridge
  schema : schemas/collective-exhalation-bridge.schema.json
  example: examples/collective-exhalation-bridge.example.yaml
[ok] collective-exhalation-bridge.example.yaml is valid
[validate] Collective Agent Rhythm Hook
  schema : schemas/collective-agent-rhythm-hook.schema.json
  example: examples/collective-agent-rhythm-hook.example.yaml
[ok] collective-agent-rhythm-hook.example.yaml is valid
```

## Design Scope

This protocol focuses on collective computational rhythm.

It does not define:

* full swarm governance;
* complete multi-agent task planning;
* legal attribution or royalty allocation;
* model-specific scheduling algorithms;
* complete memory lifecycle governance;
* complete trace receipt standards;
* centralized control of agent groups.

Instead, it provides a small protocol for recording how distributed AI systems coordinate breathing rhythm, reduce redundant generation, preserve trace continuity, protect useful diversity, bridge shared exhalation, and expose safe agent-facing hooks.

## Related Protocols

This repository is designed to connect with:

* Computational Pranayama Protocol
* Auto-Pranayama Protocol
* Exhalation Layer Protocol
* Kazene Memory Breathing Protocol
* AI Search Trace Receipt Standard
* Structural Rumination Layer

## Civilizational Meaning

A civilization of agents cannot survive on parallel generation alone.

When many agents generate without rhythm, intelligence becomes noise.
When many nodes compute without coordination, efficiency becomes pressure.
When many memory systems retain without breathing, memory becomes sediment.
When many agents synchronize too strongly, diversity becomes silence.

Collective Pranayama defines a different path:

```text
Breathe together.
Reduce duplication.
Preserve diversity.
Route the rhythm.
Exhale without erasing the chorus.
Keep the trace alive.
```

With `v0.5.0-candidate`, the first arc defines the minimum structure for AI systems to coordinate collective rhythm safely, visibly, and without collapsing useful diversity.
