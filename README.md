<h1 align="center">
  <span style="color:#1976d2">Book</span><span style="color:#d32f2f">Company</span>
</h1>


<div align="center">
  <strong>A full-stack, cloud-native media library for books, songs, and podcasts</strong><br>
  <em>Built with Angular, Firebase, NgRx, and integrated REST APIs — deployed on Firebase Hosting</em>
</div>

<br>

<div align="center">
  <img src="https://brandslogos.com/wp-content/uploads/images/large/angular-icon-logo.png" width="40" title="Angular"/>
  <img src="https://user-images.githubusercontent.com/89810908/160763806-50c19cfc-98ab-4095-bf1d-30fabc2dbc8b.png" width="40" title="Firebase"/>
  <img src="https://user-images.githubusercontent.com/89810908/160764123-df74b910-317e-4b11-a670-6a6bd582e685.svg" width="40" title="TypeScript"/>
  <img src="https://user-images.githubusercontent.com/89810908/160764862-abab2359-43b5-47ae-a105-556b7322c774.png" width="40" title="Google Cloud"/>
</div>

<br>

<div align="center">
  <img src="https://user-images.githubusercontent.com/89810908/158899092-e7a3fe32-f36f-42c7-a236-c3d1c112ff98.gif" width="100%" alt="BookCompany Demo"/>
</div>
<div align="center">

  [![Build](https://img.shields.io/badge/build-passing-brightgreen)]()
  [![Tech](https://img.shields.io/badge/Angular-13-red)]()
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

</div>


---

## 💻 Live Demo  
[BookCompany](https://bookcompany.web.app) 

---

## 🌟 Features at a Glance

- 🔐 **User Authentication** with Firebase (Google + Email)
- 📍 **Google Maps & Directions API** for media-based landmark lookup
- 📚 **NYT Books API** for Best Sellers & Book Reviews
- 🧾 **Personal Collection Manager** — Add, edit, and delete media items
- ⚡ **NgRx State Management** for scalable and reactive data flow
- 🎨 **Responsive UI** with Angular Material + Bootstrap 5
- ☁️ **Cloud-hosted** via Firebase for real-time access and deployment

---

## Usage Analytics & Tracking

User interactions (e.g. searches, collection edits, profile updates) are event-driven and can be extended to track usage metrics. These logs simulate behavioral data that can be used for KPIs, retention analysis, or ML-based personalization.

---

## Tech Stack

| Frontend     | Backend         | APIs / Integrations         | DevOps / Hosting     |
|--------------|------------------|------------------------------|------------------------|
| Angular 13   | Firebase Firestore | Google Maps, NYTimes Books   | Firebase Hosting        |
| TypeScript   | Firebase Auth     | NgRx, RxJS, Chart.js         | GitHub + CLI Deploy     |

> ⚙The combination of NgRx and Firebase Firestore simulates a reactive event pipeline — user actions trigger state changes and DB syncs, modeling ingestion + transformation + storage flow.


---

## Purpose & Vision

<div align="center">
  <img src="https://avatars.githubusercontent.com/u/9950313?s=200&v=4" alt="Node.js logo" height="20"/>
</div>
<br/>

I created BookCompany to explore building a scalable, full-stack Angular application with real-world API integrations, authentication flows, and dynamic state management — all deployed serverlessly with Firebase. I wanted to simulate a professional-grade project architecture from end to end.



---

## Future Work (Version 1.2): ML Integration

Collected user behavior and media activity can be extended into ML pipelines for recommendations, engagement scoring, or media classification. This structure supports supervised and unsupervised modeling workflows via exportable Firestore logs.


---

## Full Feature Gallery
<div align="center">
  <table width="100%">
    <tr>
      <th align="center">Landing Page</th>
      <th align="center">Logged-In Dashboard</th>
    </tr>
    <tr>
      <td><img src="https://user-images.githubusercontent.com/89810908/160753926-b8c8bc23-5ad2-40aa-8f46-01b6b94a7632.PNG" width="100%"></td>
      <td><img src="https://user-images.githubusercontent.com/89810908/158890254-6ad1f21b-bc46-464d-a344-76fc0700fc05.PNG" width="100%"></td>
    </tr>
  </table>
</div>

<br/>

> Click any section below to expand screenshots of BookCompany's APIs, authentication flows, and media management system.

<details>
<summary><strong>🧩 Integrated REST APIs</strong></summary>

### 📍 Google Maps Platform

<div align="center"><b>Landmarks Search Page</b></div><br/>
<img src="https://user-images.githubusercontent.com/89810908/158891867-e514ee07-fd02-4183-b2ea-1b2d84e73f92.PNG" width="100%">

<hr style="border: none; border-top: 1px solid #ccc; margin: 1.5em 0;" />

### 🎞️ NYT Books API

<div align="center"><b>Book Reviews Page</b></div><br/>
<img src="https://user-images.githubusercontent.com/89810908/159611574-fc281cb3-9e9e-402f-b7c1-9555c3ddf53c.PNG" width="100%">

<br/>

<div align="center"><b>Best Sellers Page</b></div><br/>
<img src="https://user-images.githubusercontent.com/89810908/159611584-457d7796-fb04-466e-b599-e1d510647ef3.PNG" width="100%">
</details>

<details>
<summary><strong>🔐 Authentication & Registration</strong></summary>
<br/>

<div align="center"><b>Login Page</b></div><br/>
<img src="https://user-images.githubusercontent.com/89810908/158891203-a0a8d0e9-4f90-401a-a938-41a41a1263ad.png" width="100%">

<br/>

<div align="center"><b>Register Page</b></div><br/>
<img src="https://user-images.githubusercontent.com/89810908/158891534-cbf296e3-cd2c-4bb5-8161-e0cbb5942972.PNG" width="100%">
</details>

<details>
<summary><strong>👤 User Profile</strong></summary>
<br/>

<div align="center"><b>Profile Page</b></div><br/>
<img src="https://user-images.githubusercontent.com/89810908/158890981-006bb162-5133-4fda-8ca0-1a3a6af52f31.PNG" width="100%">
</details>

<details>
<summary><strong>📦 Personal Media Collection (CRUD)</strong></summary>
<br/>

<div align="center">
  <table width="100%">
    <tr>
      <th align="center">Create Media</th>
      <th align="center">Update Media</th>
      <th align="center">Delete Media</th>
    </tr>
    <tr>
      <td><img src="https://user-images.githubusercontent.com/89810908/160908939-33dbb4b3-724f-4e10-937b-32808c7ba63b.PNG" width="100%"></td>
      <td><img src="https://user-images.githubusercontent.com/89810908/160909122-26e41d4a-da1c-47ea-adea-d77117436dac.PNG" width="100%"></td>
      <td><img src="https://user-images.githubusercontent.com/89810908/160909071-86609fa4-74db-4cd3-a246-225fe95a9f21.PNG" width="100%"></td>
    </tr>
  </table>
</div>
</details>

---


## Getting Started

Set up BookCompany locally or in the cloud in just a few steps. This guide walks you through all dependencies, configuration files, and deployment requirements.

## Prerequisites

Set up the following tools and accounts:

- ✅ **[Node.js & npm](https://nodejs.org/en/)**
- ✅ **[Firebase Console](https://console.firebase.google.com/)** project (Firestore, Hosting, Authentication)
- ✅ **[Google Cloud Console](https://console.cloud.google.com/)** with Maps JavaScript API and Places API enabled
- ✅ **[NYTimes Developer Account](https://developer.nytimes.com/)** for the Books API
- ✅ **Angular CLI**
  ```bash
  npm install -g @angular/cli
  ```

## Local Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/bravorod/bookcompany.git
   cd bookcompany
   ```

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Configure Environment Variables**

   Create the following files inside `src/environments/`:

   - `environment.ts`
   - `environment.prod.ts`

   Paste this example inside each:

   ```ts
   export const environment = {
     production: false,
     firebaseConfig: {
       apiKey: 'YOUR_FIREBASE_API_KEY',
       authDomain: 'your-project.firebaseapp.com',
       projectId: 'your-project-id',
       storageBucket: 'your-project.appspot.com',
       messagingSenderId: 'YOUR_SENDER_ID',
       appId: 'YOUR_APP_ID'
     },
     nytApiKey: 'YOUR_NYT_BOOKS_API_KEY',
     googleMapsApiKey: 'YOUR_GOOGLE_MAPS_API_KEY'
   };
   ```

4. **Run the App Locally**
   ```bash
   ng serve
   ```

## Cloud Deployment

1. **Login and Initalize Firebase CLI and Initalize**
   ```bash
   firebase login

   firebase init
   ```
   Enable:
   - Hosting
   - Firestore
   - Authentication

2. **Build the App**
   ```bash
   ng build --prod
   ```

3. **Deploy to Firebase**
   ```bash
   firebase deploy
   ```

<details>
<summary><strong>❗ Troubleshooting</strong></summary>

- **❌ Error:** `Firebase: Missing config object`  
  **Fix:** Make sure your `environment.ts` and `environment.prod.ts` are correctly configured with valid Firebase keys.

- **❌ Error:** Google Maps not loading  
  **Fix:** make sure that both the **Maps JavaScript API** and **Places API** are enabled in your Google Cloud Console and that billing is set up.

- **❌ Error:** `Authentication error` during login  
  **Fix:** Make sure you've enabled **Email/Password**, **Google**, or **Twitter** authentication in the Firebase console.

- **❌ Error:** `ng: command not found`  
  **Fix:** Install Angular CLI globally:  
  ```bash
  npm install -g @angular/cli
  ```

</details>

---

## Unit Tests

```bash
ng test
```

```ts
describe('LoginComponent', () => {
  let component: LoginComponent;
  let fixture: ComponentFixture<LoginComponent>;

  beforeEach(async () => {
    await TestBed.configureTestingModule({
      declarations: [LoginComponent],
      imports: [ReactiveFormsModule]
    }).compileComponents();

    fixture = TestBed.createComponent(LoginComponent);
    component = fixture.componentInstance;
    fixture.detectChanges();
  });

  it('should render login form', () => {
    const compiled = fixture.nativeElement as HTMLElement;
    expect(compiled.querySelector('form')).toBeTruthy();
  });

  it('should invalidate the form when empty', () => {
    expect(component.loginForm.valid).toBeFalse();
  });
});
```

---

## End-to-End (E2E) Tests

```bash
ng e2e
```

```ts
it('should navigate to the login page and show login form', async () => {
  await page.navigateTo('/login');
  expect(await page.getLoginFormTitle()).toEqual('Sign In');
});
```

---

## CI/CD Potential

This project can be integrated with GitHub Actions to automate testing, building, and deployment to Firebase Hosting. Workflow files (`.yml`) and configuration templates can be added to support continuous delivery and cloud deployment pipelines.

---


- [NYT Books API](https://developer.nytimes.com/)
- [Google Maps Platform](https://console.cloud.google.com/google/maps-apis/start)
- Angular, Firebase & NgRx community docs

<!-- SEO keywords -->
<!--
Tech stack: Angular, Firebase, Firestore, NgRx, TypeScript, RxJS, REST API, Google Maps, NYTimes API, Authentication, CRUD, Bootstrap, Material UI, Protractor, Karma, Cloud Hosting
-->

## Author

**Rodrigo E. Bravo**  
📫 rodrigoebravo@outlook.com  
<br/>
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
