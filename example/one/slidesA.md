<!SLIDE title-slide>
.notes run through what im going to talk about

# Pages #


!SLIDE center full-page
.notes show page in browser

![octocat](home_page.png)


!SLIDE center full-page
.notes show page in browser

![octocat](home_page_editable.png)

!SLIDE center full-page
.notes show page in browser

![octocat](home_page_buttons.png)

!SLIDE center full-page
.notes show page in browser

![octocat](home_page.png)

!SLIDE full-page center
.notes controller like air traffic controller


# Quick runthrough #

![octocat](mvc.png)

!SLIDE smaller
.notes controller like air traffic controller
# Controller #
	@@@ ruby
	def home_page
      @home_page_buttons = Database.find 'home_page_buttons'
	end

!SLIDE center full-page
.notes show page in browser

![octocat](buttons_database.png)


!SLIDE center full-page
.notes show page in browser

![octocat](before.png)

!SLIDE center full-page
.notes show page in browser

![octocat](home_buttons_view.png)
