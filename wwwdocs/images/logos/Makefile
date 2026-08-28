.PHONY: scaled

scaled:
	mkdir scaled || true
	find . -maxdepth 1 -name "*.png" -or -name "*.jpg" -or -name "*.tiff" \
		| xargs mogrify -resize '720x360>' -path scaled
