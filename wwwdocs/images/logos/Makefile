.PHONY: scaled

scaled:
	mkdir scaled || true
	find . -name "*.png" -or -name "*.jpg" -or -name "*.tiff" \
		| xargs mogrify -resize '720x360>' -path scaled
