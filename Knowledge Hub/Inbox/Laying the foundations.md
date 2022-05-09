# Laying the foundations
Date: Jan 6, 2022

## Summary

## Chapters
1. **What is Design system?**
	1. Design systems bring order and consistency to digital products. They help to protect the brand, elevate the user experience, and increase the speed and efficiency of how we design and build products. They are a source of truth and a system of record for our design decisions. They hold us to high standards, keep teams on the same page, and help to onboard new team members. They document the why, when, where, and how.
	2. Continous work, never finished.
	3. The real test of a design system is whether the design and build mirror each other, and if you and your team consistently use the elements you establish rather than needlessly creating new ones.
2. **Selling Design System**
	1. Solving problems is a big part of the value proposition of a design system
	2. If you believe in design systems and want to see one thrive at your company, you need a compelling case that’s tailored to your business, team, and user needs
	3. [[bureaucracy]] / office politics is always in play.
	 > Selling a design system isn’t a stage of the process. It’s ongoing.
3. **Laying the Foudations**
	1. Brand is a core component to Design System.
	> Brand foundations help to keep everyone on the same page, speaking the same language, and working as a team — rather than a collection of individuals doing their own thing.
	2. Rather than focusing on marketing v/s product, focus on [[Digital Foundations]]
	3. *Hash out your mission, values, standards, and principles.*
	4. Create [[Brand Identity]]
	5. Include copywriters to create a brand tone of voice.
	6. In addition to tone and vocabulary, your Digital Foundations should include guidelines for formatting.
		> Don’t assume your international audience perceives everything the same way you do
	7. Use your Digital Foundations to document your standards, raise awareness by educating your team on accessibility issues in digital design, and write guidelines for how to design for accessibility. Example. https://www.microsoft.com/design/inclusive/
	8. Responsove design.
	9. Good documentation which you can externalise.
	10. *Digital Foundations are more all-encompassing, covering brand identity, formatting, and “a shared vocabulary for design”, as IBM  put it*. Design system documentation is more specific — it covers components and patterns created using the Digital Foundations as a starting point, but is specifically for use in a particular website or product.
4. **Design System Model**
	> It’s important your team aligns on a design system model and a shared language that everybody understands. The less jargon you use, the better.
	1. 👉 be sure to include property-specific foundations in your design system foundation. such as diff text styles for web and mobile.
	 #### Foundations Model
	 
	 ![[Drawing 2022-01-02 15.04.20.excalidraw.png]]
	2. **i. Components**
			1. These are the smaller building blocks of a digital product. Components are distinctive user interface (UI) elements that are used repetitively throughout a product. Examples include: buttons, form inputs, selects, textareas, radio buttons, checkboxes, range sliders, toggles, avatars, tooltips, and so on.
			2. Using conventional components (that aren’t ‘overstyled’) makes sure that inputs and actionable items are instantly recognisable to users.
			3. Good to show all states and interactivity.
		1. **Patterns**
			1. These are the larger building blocks of a digital product. Patterns refer to recurring or ever-present elements or practices throughout a product. A pattern can often be comprised of established foundations and components — for example, a card pattern may feature a header and a description, using a couple of different text styles (foundations), and a button (component).
			2. Examples include: navigation, footer, modals, alerts, notifications, tables, feed cards, product cards, image galleries, carousels, feature or masthead areas, pagination, breadcrumbs, and so on.
			3. Patterns are often modular, meaning they’re designed to pair well with other patterns to tell marketing stories, sell products, present content, cross-sell, and so on.
			4. Good to name your patterns and show all variations
	3. **Templates**
		1. In digital terms, a template is a consistent layout that is used multiple times throughout a website, and are populated with different content each time they’re used. Common examples of templates include an article or a blog post.
		2. The fewer templates you use, the easier and less expensive the build and maintenance will be.
	4. **Pages** 
		1. A page is either the application of a template, or a bespoke one-off web page
	5. **Design system in digital products** 
		1. ![[Pasted image 20220102151201.png]]
		2. *The big difference between a pattern and a feature is their complexity. A pattern might perform one or two functions, and can be deployed in a number of different ways as a reusable element. A feature can perform many functions or one specific function, and may be comprised of multiple patterns.*
		3. Each feature can have a multi-step ‘user journey’ to perform certain tasks. In a way, you could look at features as being ‘super patterns’, but that name doesn’t hold much credibility. On the surface, a feature is an assortment of foundations, components, and patterns pulled together to perform a specific task(s). But each interactive part of a feature can go several layers deep, creating more of a user journey.
		4. *A screen is the culmination of all your foundations, components, patterns, and features coming together. It’s a snapshot in time of someone using your product, or a step in their user journey.*
		5. For example, a banking product might have a ‘screen’ dynamically created and tailored to a specific user account, user type, and preference settings. 
	6. Allow for flexibility, documents the when, why, and how, better together.
	 > Ground your work in reality. Design for all scenarios, not just the best case scenarios. Don’t try to fit the content to your design. Design for the content.
5. **Getting started**
	> The first app I opened when we started wasn’t Sketch. It was Google Docs. You need to clearly articulate the problems you’re solving first.
	2. **Iterative Approach**
		1. Find your team ➡ Interface Audits ➡ Color Audits ➡ Visual audits ➡ Code Audit
			1. An ‘interface audit’ is a broad term for conducting audits on a digital product.
			2. A ‘visual audit’ is a design-based audit of what you can see in a digital product, focussed on foundations, components, and patterns.
			3. You could focus the scope of a visual audit, and do only a ‘pattern audit’ or a ‘component audit’.
			4. A ‘code audit’ is an audit of what you can’t see, but what makes everything work behind the scenes: CSS, HTML, JavaScript, and so on.
			5.  A ‘colour audit’ takes stock of colours used across all digital properties.
			6. A ‘content audit’ maps out what you’re communicating and where.
		2. Refinement while exploring: ➡Take time to explore each problem area first, then refine. Don’t bypass the opportunity for design exploration altogether.
	3. **Wholesale Approach**
	4. **Or Mixed approach**
6. **Systemising the Design**
	1. Having a design system library
		1. The library should contain reusable elements from your design system that you commonly use in your design mockups, such as text styles, form inputs, and buttons. It should also include all their variations and states (e.g. a text input’s placeholder, value, hover, error, and disabled states)
		2. The data/text content/value also needs to be editable, which means your components need to be responsive so they will work with variable amounts of content.
		3. Following Naming conventions
		4. **Color guidelines** ➡ Primary colors, utility colors, and secondary, tertiary or accent colors.
		5. **Limited Text styles**
		6. **Editable components**
			1. Easily and quickly insert pre-made components into their designs.
			2. Edit the component’s content.
			3. Switch between its different states (we’ll cover those next).
			4. Sync any updates made to the component
		7. **Pattern Library** that is **Responsive**
		8. Design token and cide variables
7. **Documentation**
	>  The guidelines and decisions you make when designing a system are no good just in your head. They’re not ‘need to know’. Everyone on your team needs to know.
		 Document as you go, show them in action, and mention do and dont´s
	2. color,Brand identity, typography, components, pattern, Grids, layout, and spacing, avatars and other small things, design tokens.
8. **Gallery**
	1. https://culture.basicagency.com/our-way/
	2. https://www.bbc.co.uk/gel/guidelines/category/foundations
	3. https://airbnb.design
	4. https://www.lightningdesignsystem.com
	5. https://atlassian.design/
	6. https://marvelapp.com/styleguide/overview/introduction
	7. https://primer.style
	8. https://www.carbondesignsystem.com/components/button/usage
	9. https://seeds.sproutsocial.com
	10. https://solid.buzzfeed.com/release-notes.html
	11. https://thumbprint.design/guide/product/color/
9. **Maintaining a design system**
	 > The goal is to educate, not enforce. Approach the management of a design system from a teaching and collaborating perspective, not as the ruling authority.
	2. Work with shared design patterns
	3. Work with Patterns
	4. Keep documentation upto date: Make it part of your process to update design libraries and any documentation when you create new, or update existing design system elements.
	5. Keep design and code in sync
	6. Keep team in loop
	7. Form a design system team and lead. 
##  Problems the author is trying to solve.

## Tags

## Links from this Page
```dataview  
	LIST FROM outgoing([[]])
```

## Prereading
