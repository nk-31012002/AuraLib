# 📱 AuraLib — Document Management & Distribution Platform

AuraLib is a native Android application developed to serve as an enterprise-grade digital library and document-sharing repository. Designed around strict Role-Based Access Control (RBAC), the platform provides distinct execution lifecycles for administrative content managers and global consumers, backed by asynchronous remote streaming, binary compilation tracking, and deep system persistence.

---

## 🌟 Core Functionality

### 🔐 Multi-Tier Security & Authentication
* **Role-Based Provisioning:** Used cloud authorization token filtering to dynamically split app environments into consumer views or write-enabled executive console layers.
* **Identity Protection:** Fully orchestrates account loops including registration validations, secure inputs, transactional password resets, and hardware email verification constraints.

### 📄 Dynamic Content Streaming & Processing
* **On-Demand Binary Streaming:** Streams remote multi-megabyte PDF files securely down into a sandbox-isolated cache layer for smooth programmatic reading.
* **Asynchronous Metadata Extraction:** Reads file attributes directly from binary network locations to dynamically compute and format disk footprint sizes (KB/MB) and index page-lengths on deep worker threads.

### 💬 Engagement & Offline Indexing
* **Localized Bookmarking:** Features a dual database write pattern allowing consumers to toggle network syncs or capture document indices to local database references.
* **Catalogs & Interaction:** Provides asynchronous transaction scopes to track system-wide view telemetry, download thresholds, and nested conversational user reviews.

---

## 🛠️ Technical Implementations

* **Language Platform:** Kotlin (Native Android SDK targeting API 33)
* **Storage & Infrastructure:**
  * **Firebase Authentication:** Handles profile security verification maps.
  * **Firebase Realtime Database:** Orchestrates highly organized NoSQL tree schemas designed for high-concurrency read operations.
  * **Firebase Storage:** Serves as the central repository hosting file blobs and visual assets safely behind encrypted URL protocols.
* **Document Engine:** `android-pdf-viewer` (Executes low-level frame renderings from remote byte streams directly inside standard view controllers).
* **Caching Engine:** `Glide` (Performs non-blocking background network lookups, asset parsing, and image view recycling).
* **Jetpack UI Suite:** Modern Layout Flow layouts, programmatic view models, and `ViewBinding` integration layers ensuring complete null-safety constraints across all layouts.

---

## 🚀 Installation & Local Environment Setup

Ensure the local Android Studio layout engine is updated to support Kotlin compilation targets.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nk-31012002/TalentStream.git
   cd auralib

2. **Backend Authentication Setup:**
   -Attach your local system credentials file (google-services.json) into the root directory framework path (/app/).

3. **Compile Dependencies:**
   ```bash
   ./gradlew build

5. **Execute App Target:**
   -Boot an emulator target running API level 26+ and launch the engine:
   ```bash
   ./gradlew installDebug
