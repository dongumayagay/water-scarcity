<script>
	import { initializeApp } from 'firebase/app';
	import { getAnalytics, isSupported } from 'firebase/analytics';
	import { browser } from '$app/env';

	import '../app.css';
	const firebaseConfig = {
		apiKey: 'AIzaSyDZ6u1Wp5RD1VTSA6Mmu4c5WcEzYFYuj_k',
		authDomain: 'water-scarcity-cw.firebaseapp.com',
		projectId: 'water-scarcity-cw',
		storageBucket: 'water-scarcity-cw.appspot.com',
		messagingSenderId: '571936556718',
		appId: '1:571936556718:web:8e9904aae87d7f474f4f3f',
		measurementId: 'G-9KYFMWCX64'
	};
	const app = initializeApp(firebaseConfig);
	// const analytics = getAnalytics(app);
	let analytics;
	if (browser && isSupported) {
		analytics = getAnalytics(app);
	}
</script>

<svelte:head><title>Water Scarcity</title></svelte:head>
<slot />
