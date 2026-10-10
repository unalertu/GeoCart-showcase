<p align="center">
  <img src="assets/logo.png" width="180" alt="GeoCart logo">
</p>

<h1 align="center">GeoCart</h1>
<p align="center"><strong>Shopping reminders that appear where they become useful.</strong></p>
<p align="center"><a href="https://geocart.unlertu.workers.dev/">Product website</a></p>

## Product overview

GeoCart is a location-aware shopping companion for people who remember what they need only after leaving the store behind. Users build reusable lists, associate them with saved stores, and choose the distance at which GeoCart should send a reminder.

## Product highlights

- Create, organize, and reuse shopping lists instead of rebuilding them for every trip.
- Discover nearby stores on an interactive map and save frequently visited locations.
- Configure a reminder distance independently for each saved store.
- Continue using saved lists and store reminders when network access is limited.
- Use background region monitoring and local notifications for timely alerts.
- Open a saved destination in the preferred maps application for navigation.
- Keep location permissions optional and under the user's control.

## Product approach

GeoCart connects a list with the place where it matters. Its mobile experience is local-first: saved data remains available on the device, permissions are requested only for features that need them, and the product does not depend on advertising or third-party analytics trackers.

## Technology

| Area | Technology |
| --- | --- |
| Mobile application | React Native 0.81, Expo 54, and TypeScript |
| Navigation | Expo Router with typed routes |
| Maps and location | React Native Maps, Expo Location, and background region monitoring |
| Reminders | Expo Notifications and Expo Task Manager |
| Local state | Zustand and AsyncStorage |
| Interface | NativeWind, Reanimated, Gesture Handler, and map clustering |
| Purchases | RevenueCat |
| Product website | Next.js 15, React 19, Tailwind CSS, Framer Motion, and Cloudflare Workers |
| Quality | Jest, ESLint, and TypeScript checks |

## Availability

The product website is available at [geocart.unlertu.workers.dev](https://geocart.unlertu.workers.dev/). The application source is private; this repository is the public product showcase.
