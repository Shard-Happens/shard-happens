# System design interviews, from the interviewer's side

[Shard Happens](https://shardhappens.dev/) explains system design interview problems from the interviewer's side of the table: what is being looked for, and the red flags that cost marks.

This repository is an index of its 76 problems, each with a short summary and a link to its page. 13 of them are free to read in full, and their summaries carry the design diagram and the red and green flags.

## Start here

- [Estimation cheat sheet](cheat-sheet.md): seconds in a day, sizes, latencies and the formulas
- [Capacity calculator](https://shardhappens.dev/tools/capacity-calculator/)
- [Gathering Requirements](https://shardhappens.dev/guides/requirements/): The first five minutes decide what gets designed. Ask the few questions whose answers change the design, write the answers down and move on.
- [Back-of-the-Envelope Estimation](https://shardhappens.dev/guides/estimation/): Quick arithmetic tells you which kind of system you are building. Aim for the right order of magnitude in two minutes rather than a precise figure.
- [Calculating Load](https://shardhappens.dev/guides/load/): Guide 2 gives an average and a peak. This guide turns them into what the system must actually survive: load per API, load on the database, the shape of traffic over time, and spikes.
- [Estimating Capacity](https://shardhappens.dev/guides/capacity/): Guide 3 ends with a peak request rate. This guide follows that rate into the parts that actually run out: servers, connections, database rows, disk and queues, and asks what is left when one of them fails.

## Problems

Each problem has a score out of 10 and a level. "Free account" and "Premium" pages show their framing and questions to everyone.

### Easy (8)

| # | Problem | Score | AI | Access | Full page |
|---|---|---|---|---|---|
| 1 | [URL Shortener](problems/url-shortener.md) | 3/10 |  | Free | [Read](https://shardhappens.dev/problems/url-shortener/) |
| 9 | [Unique ID Generator](problems/unique-id-generator.md) | 2/10 |  | Free | [Read](https://shardhappens.dev/problems/unique-id-generator/) |
| 10 | [Leaderboard](problems/leaderboard.md) | 3/10 |  | Free | [Read](https://shardhappens.dev/problems/leaderboard/) |
| 29 | [Like Button](problems/like-button.md) | 2/10 |  | Free | [Read](https://shardhappens.dev/problems/like-button/) |
| 30 | [Feature Toggles for One Application](problems/feature-toggles.md) | 3/10 |  | Free | [Read](https://shardhappens.dev/problems/feature-toggles/) |
| 31 | [Token Bucket Rate Limiter](problems/token-bucket-rate-limiter.md) | 3/10 |  | Free | [Read](https://shardhappens.dev/problems/token-bucket-rate-limiter/) |
| 32 | [Autocomplete Box](problems/autocomplete-box.md) | 3/10 |  | Free | [Read](https://shardhappens.dev/problems/autocomplete-box/) |
| 33 | [Nearby Places Search](problems/nearby-places.md) | 3/10 |  | Free | [Read](https://shardhappens.dev/problems/nearby-places/) |

### Medium (30)

| # | Problem | Score | AI | Access | Full page |
|---|---|---|---|---|---|
| 2 | [Proximity Service](problems/proximity-service.md) | 6/10 |  | Premium | [Read](https://shardhappens.dev/problems/proximity-service/) |
| 5 | [Distributed Rate Limiter](problems/rate-limiter.md) | 4/10 |  | Premium | [Read](https://shardhappens.dev/problems/rate-limiter/) |
| 6 | [News Feed](problems/news-feed.md) | 6/10 |  | Premium | [Read](https://shardhappens.dev/problems/news-feed/) |
| 11 | [Notification System](problems/notification-system.md) | 4/10 |  | Free account | [Read](https://shardhappens.dev/problems/notification-system/) |
| 12 | [Typeahead](problems/typeahead.md) | 5/10 |  | Premium | [Read](https://shardhappens.dev/problems/typeahead/) |
| 13 | [RAG Knowledge Assistant](problems/rag-knowledge-assistant.md) | 5/10 | AI | Free | [Read](https://shardhappens.dev/problems/rag-knowledge-assistant/) |
| 14 | [LLM Gateway](problems/llm-gateway.md) | 6/10 | AI | Free | [Read](https://shardhappens.dev/problems/llm-gateway/) |
| 16 | [Web Crawler](problems/web-crawler.md) | 5/10 |  | Free account | [Read](https://shardhappens.dev/problems/web-crawler/) |
| 17 | [Feature Flag Service](problems/feature-flag-service.md) | 4/10 |  | Premium | [Read](https://shardhappens.dev/problems/feature-flag-service/) |
| 20 | [Distributed Job Scheduler](problems/job-scheduler.md) | 5/10 |  | Free account | [Read](https://shardhappens.dev/problems/job-scheduler/) |
| 22 | [Likes and View Counter](problems/likes-view-counter.md) | 4/10 |  | Premium | [Read](https://shardhappens.dev/problems/likes-view-counter/) |
| 23 | [Resumable Upload Service](problems/resumable-upload-service.md) | 4/10 |  | Free account | [Read](https://shardhappens.dev/problems/resumable-upload-service/) |
| 24 | [Machine ID Leases](problems/machine-id-leases.md) | 5/10 |  | Premium | [Read](https://shardhappens.dev/problems/machine-id-leases/) |
| 25 | [Distributed Cache](problems/distributed-cache.md) | 6/10 |  | Premium | [Read](https://shardhappens.dev/problems/distributed-cache/) |
| 27 | [LLM Evaluation Platform](problems/llm-evaluation-platform.md) | 6/10 | AI | Premium | [Read](https://shardhappens.dev/problems/llm-evaluation-platform/) |
| 36 | [Video Streaming Service](problems/video-streaming.md) | 6/10 |  | Free account | [Read](https://shardhappens.dev/problems/video-streaming/) |
| 40 | [Online Feature Store](problems/feature-store.md) | 6/10 | AI | Premium | [Read](https://shardhappens.dev/problems/feature-store/) |
| 42 | [Webhook Delivery](problems/webhook-delivery.md) | 5/10 |  | Free account | [Read](https://shardhappens.dev/problems/webhook-delivery/) |
| 45 | [Calendar](problems/calendar.md) | 6/10 |  | Premium | [Read](https://shardhappens.dev/problems/calendar/) |
| 47 | [Online Auction](problems/online-auction.md) | 6/10 |  | Premium | [Read](https://shardhappens.dev/problems/online-auction/) |
| 48 | [Log Aggregation](problems/log-aggregation.md) | 5/10 |  | Premium | [Read](https://shardhappens.dev/problems/log-aggregation/) |
| 50 | [Content Delivery Network](problems/cdn.md) | 6/10 |  | Premium | [Read](https://shardhappens.dev/problems/cdn/) |
| 54 | [Load Balancer](problems/load-balancer.md) | 5/10 |  | Free account | [Read](https://shardhappens.dev/problems/load-balancer/) |
| 57 | [Document Extraction Pipeline](problems/document-extraction.md) | 5/10 | AI | Premium | [Read](https://shardhappens.dev/problems/document-extraction/) |
| 63 | [Sign-In with Passkeys](problems/passkey-sign-in.md) | 5/10 |  | Premium | [Read](https://shardhappens.dev/problems/passkey-sign-in/) |
| 67 | [Design a Data Labelling Platform](problems/labelling-platform.md) | 5/10 | AI | Premium | [Read](https://shardhappens.dev/problems/labelling-platform/) |
| 68 | [TLS Certificate Automation](problems/certificate-automation.md) | 5/10 |  | Premium | [Read](https://shardhappens.dev/problems/certificate-automation/) |
| 71 | [Ride Dispatch](problems/ride-dispatch.md) | 6/10 |  | Free account | [Read](https://shardhappens.dev/problems/ride-dispatch/) |
| 72 | [Game Matchmaking](problems/game-matchmaking.md) | 6/10 |  | Premium | [Read](https://shardhappens.dev/problems/game-matchmaking/) |
| 73 | [Design a Deployment System](problems/deployment-controller.md) | 5/10 |  | Premium | [Read](https://shardhappens.dev/problems/deployment-controller/) |

### Hard (36)

| # | Problem | Score | AI | Access | Full page |
|---|---|---|---|---|---|
| 3 | [Ticket Booking](problems/ticket-booking.md) | 8/10 |  | Premium | [Read](https://shardhappens.dev/problems/ticket-booking/) |
| 4 | [Top-K Trending](problems/top-k-trending.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/top-k-trending/) |
| 7 | [Chat Messaging](problems/chat-messaging.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/chat-messaging/) |
| 15 | [AI Agent Platform](problems/ai-agent-platform.md) | 8/10 | AI | Free | [Read](https://shardhappens.dev/problems/ai-agent-platform/) |
| 18 | [Durable Message Queue](problems/durable-message-queue.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/durable-message-queue/) |
| 19 | [LLM Inference Serving](problems/llm-inference-serving.md) | 7/10 | AI | Free | [Read](https://shardhappens.dev/problems/llm-inference-serving/) |
| 21 | [Payment Ledger](problems/payment-ledger.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/payment-ledger/) |
| 26 | [Metrics Monitoring and Alerting](problems/metrics-monitoring-alerting.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/metrics-monitoring-alerting/) |
| 34 | [File Sync Service](problems/file-sync.md) | 8/10 |  | Premium | [Read](https://shardhappens.dev/problems/file-sync/) |
| 35 | [Design an AI Code Execution Sandbox](problems/ai-code-sandbox.md) | 7/10 | AI | Premium | [Read](https://shardhappens.dev/problems/ai-code-sandbox/) |
| 37 | [Recommendation System](problems/recommendation-serving.md) | 7/10 | AI | Premium | [Read](https://shardhappens.dev/problems/recommendation-serving/) |
| 38 | [Search Engine](problems/search-engine.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/search-engine/) |
| 39 | [Video Conferencing](problems/video-conferencing.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/video-conferencing/) |
| 41 | [Authorization Service](problems/authorization-service.md) | 8/10 |  | Premium | [Read](https://shardhappens.dev/problems/authorization-service/) |
| 43 | [Change Data Capture Pipeline](problems/change-data-capture.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/change-data-capture/) |
| 44 | [Distributed Key-Value Store](problems/key-value-store.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/key-value-store/) |
| 46 | [Content Moderation](problems/content-moderation.md) | 7/10 | AI | Premium | [Read](https://shardhappens.dev/problems/content-moderation/) |
| 49 | [Usage-Based Billing](problems/usage-billing.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/usage-billing/) |
| 51 | [Exchange Order Book](problems/order-book.md) | 8/10 |  | Premium | [Read](https://shardhappens.dev/problems/order-book/) |
| 52 | [Distributed Tracing](problems/trace-collection.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/trace-collection/) |
| 53 | [GPU Cluster Scheduler](problems/gpu-scheduler.md) | 7/10 | AI | Premium | [Read](https://shardhappens.dev/problems/gpu-scheduler/) |
| 55 | [Live Speech Transcription](problems/speech-transcription.md) | 7/10 | AI | Premium | [Read](https://shardhappens.dev/problems/speech-transcription/) |
| 56 | [Point-in-Time Training Data](problems/training-dataset.md) | 7/10 | AI | Premium | [Read](https://shardhappens.dev/problems/training-dataset/) |
| 58 | [LSM Storage Engine](problems/storage-engine.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/storage-engine/) |
| 59 | [Road Navigation Service](problems/road-navigation.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/road-navigation/) |
| 60 | [Online Schema Migration](problems/schema-migration.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/schema-migration/) |
| 61 | [Real-Time Ad Bidding](problems/ad-bidding.md) | 8/10 |  | Premium | [Read](https://shardhappens.dev/problems/ad-bidding/) |
| 62 | [Stream Join](problems/stream-join.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/stream-join/) |
| 64 | [Training Checkpoint Service](problems/training-checkpoint.md) | 7/10 | AI | Premium | [Read](https://shardhappens.dev/problems/training-checkpoint/) |
| 65 | [Database Sharding and Resharding](problems/resharding.md) | 8/10 |  | Premium | [Read](https://shardhappens.dev/problems/resharding/) |
| 66 | [Database Backup and Restore](problems/backup-restore.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/backup-restore/) |
| 69 | [Service Discovery](problems/service-discovery.md) | 7/10 |  | Premium | [Read](https://shardhappens.dev/problems/service-discovery/) |
| 70 | [Distributed Object Store](problems/object-store.md) | 8/10 |  | Premium | [Read](https://shardhappens.dev/problems/object-store/) |
| 74 | [Payment Fraud Detection](problems/payment-fraud-detection.md) | 7/10 | AI | Free account | [Read](https://shardhappens.dev/problems/payment-fraud-detection/) |
| 75 | [Ad Click Prediction System](problems/ad-click-prediction.md) | 7/10 | AI | Premium | [Read](https://shardhappens.dev/problems/ad-click-prediction/) |
| 76 | [Real-Time Voice Agent](problems/voice-agent.md) | 7/10 | AI | Free | [Read](https://shardhappens.dev/problems/voice-agent/) |

### Expert (2)

| # | Problem | Score | AI | Access | Full page |
|---|---|---|---|---|---|
| 8 | [Collaborative Editor](problems/collaborative-editor.md) | 9/10 |  | Premium | [Read](https://shardhappens.dev/problems/collaborative-editor/) |
| 28 | [Consensus-Backed Coordination Service](problems/coordination-service.md) | 9/10 |  | Premium | [Read](https://shardhappens.dev/problems/coordination-service/) |

---

Text and images © Shard Happens, under [CC BY-NC-ND 4.0](LICENSE): share them with a link to https://shardhappens.dev/, not for commercial use and not in a changed form.

This repository is generated from the site's content. Changes made here are overwritten; [tell us](https://shardhappens.dev/contact/) about a mistake instead.
