<script lang="ts">
	import Profile from '@components/profile/Profile.svelte';
	import PersonalInformation from '@components/profile/PersonalInformation.svelte';
	import Notifications from '@components/profile/Notifications.svelte';

	let { children } = $props();
</script>

<div class="bg-gray-50">
	<div class="mx-auto max-w-7xl py-12 sm:px-6 sm:py-24 lg:px-8">
		<div class="divide-y divide-gray-900/10">
			<Profile />
			<PersonalInformation />
			<Notifications />
		</div>
	</div>
</div>
