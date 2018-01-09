minetest.register_node("evenmoreblocks:pure_stone", {
    description = "Purified Stone",
    tiles = {"pure_stone.png"},
    groups = {cracky = 2},
    drop = 'default:stone',
})
minetest.register_craft({
    type = "cooking",
    output = "evenmoreblocks:pure_stone",
    recipe = "default:stone",
    cooktime = 20,
})
minetest.register_node("evenmoreblocks:pure_stone_brick", {
    description = "Purified Stone Brick",
    tiles = {"pure_stone_brick.png"},
    groups = {cracky = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:pure_stone_brick 4',
	recipe = {
		{'evenmoreblocks:pure_stone', 'evenmoreblocks:pure_stone'},
		{'evenmoreblocks:pure_stone', 'evenmoreblocks:pure_stone'},
	}
})
minetest.register_node("evenmoreblocks:packed_ice_brick", {
    description = "Pack Ice Brick",
    tiles = {"pack_ice_brick.png"},
    groups = {cracky = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:packed_ice_brick 4',
	recipe = {
		{'xdecor:packed_ice', 'xdecor:packed_ice'},
		{'xdecor:packed_ice', 'xdecor:packed_ice'},
	}
})
minetest.register_node("evenmoreblocks:small_obsidian_brick", {
    description = "Small Obsidian Brick",
    tiles = {"small_obsidian_brick.png"},
    groups = {cracky = 1, level = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:small_obsidian_brick',
	recipe = {
		{'default:obsidianbrick'},
	}
})
minetest.register_node("evenmoreblocks:hot_obsidian_brick", {
    description = "Hot Obsidian Brick",
    tiles = {"hot_obsidian_brick.png"},
    paramtype = "light",
    light_source = 7,
    groups = {cracky = 1, level = 2},
})
minetest.register_craft({
    type = "cooking",
    output = "evenmoreblocks:hot_obsidian_brick",
    recipe = "default:obsidianbrick",
    cooktime = 20,
})
minetest.register_node("evenmoreblocks:ice_lamp", {
    description = "Ice Lamp",
    tiles = {"ice_lamp.png"},
    paramtype = "light",
    light_source = 7,
    groups = {cracky = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:ice_lamp',
	recipe = {
		{'default:ice','default:torch', 'default:ice'},
		{'default:ice','default:glass', 'default:ice'},
		{'default:ice','default:torch', 'default:ice'},
	}
})
minetest.register_node("evenmoreblocks:stone_tile_pillar", {
    description = "Stone Tile Pillar",
    tiles = {
		"stone_tile_pillar_top.png",
		"stone_tile_pillar_top.png",
		"stone_tile_pillar.png",
	},
    paramtype2 = "facedir",
    on_place = minetest.rotate_node,
    groups = {cracky = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:stone_tile_pillar 3',
	recipe = {
		{'xdecor:stone_tile'},
		{'xdecor:stone_tile'},
		{'xdecor:stone_tile'},
	}
})
minetest.register_node("evenmoreblocks:obsidian_pillar", {
    description = "Stone Tile Pillar",
    tiles = {
		"obsidian_pillar_top.png",
		"obsidian_pillar_top.png",
		"obsidian_pillar_side.png",
	},
    paramtype2 = "facedir",
    on_place = minetest.rotate_node,
    groups = {cracky = 1, level = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:obsidian_pillar 3',
	recipe = {
		{'default:obsidian_block'},
		{'default:obsidian_block'},
		{'default:obsidian_block'},
	}
})
minetest.register_node("evenmoreblocks:stacked_desert_tile", {
    description = "Stacked Desert Stone Tile",
    tiles = {"stacked_desert_tile.png"},
    groups = {cracky = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:stacked_desert_tile 4',
	recipe = {
		{'xdecor:desertstone_tile', 'xdecor:desertstone_tile'},
		{'xdecor:desertstone_tile', 'xdecor:desertstone_tile'},
	}
})
minetest.register_node("evenmoreblocks:desert_stone_pillar", {
    description = "Desert Stone Pillar",
    tiles = {
		"desert_stone_tile_pillar_top.png",
		"desert_stone_tile_pillar_top.png",
		"desert_stone_tile_pillar.png",
	},
    paramtype2 = "facedir",
    on_place = minetest.rotate_node,
    groups = {cracky = 1, level = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:desert_stone_pillar 3',
	recipe = {
		{'default:desert_stone'},
		{'default:desert_stone'},
		{'default:desert_stone'},
	}
})
minetest.register_node("evenmoreblocks:jungle_wood_tile", {
    description = "Jungle Wood Tile",
    tiles = {"jungle_wood_tile.png"},
    groups = {choppy = 2,level = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:jungle_wood_tile 5',
	recipe = {
		{'', 'default:wood', ''},
		{ 'default:wood','default:junglewood', 'default:wood'},
		{'', 'default:wood', ''},
	}
})
minetest.register_node("evenmoreblocks:desert_runestone", {
    description = "Desert Runestone",
    tiles = {"desert_stone_rune.png"},
    groups = {cracky = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:desert_runestone 8',
	recipe = {
		{'default:desert_stone', 'default:desert_stone', 'default:desert_stone'},
		{ 'default:desert_stone','', 'default:desert_stone'},
		{'default:desert_stone', 'default:desert_stone', 'default:desert_stone'},
	}
})
minetest.register_node("evenmoreblocks:obsidian_runestone", {
    description = "Obsidian Runestone",
    tiles = {"obsidian_rune.png"},
    groups = {cracky = 1,level = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:obsidian_runestone 4',
	recipe = {
		{'default:obsidian','default:obsidian', 'default:obsidian'},
		{'default:obsidian','', 'default:obsidian'},
		{'default:obsidian','default:obsidian', 'default:obsidian'},
},
})
minetest.register_node("evenmoreblocks:hard_clay_brick", {
    description = "Hard Clay Brick",
    tiles = {"hard_clay_brick.png"},
    groups = {cracky = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:hard_clay_brick 4',
	recipe = {
		{'xdecor:hard_clay', 'xdecor:hard_clay'},
		{'xdecor:hard_clay', 'xdecor:hard_clay'},
	}
})
minetest.register_craftitem("evenmoreblocks:lava_blob", {
    description = "Lava Blob",
    inventory_image = "lava_blob.png",
})
minetest.register_craft({
    type = "cooking",
    output = "evenmoreblocks:lava_blob",
    recipe = "default:obsidian",
    cooktime = 20,
})
minetest.register_node("evenmoreblocks:lava_lamp", {
    description = "Lava Lamp",
    tiles = {"lava_lamp.png"},
    paramtype = "light",
    light_source = 12,
    groups = {cracky = 1,level = 2},
})
minetest.register_craft({
	output = 'evenmoreblocks:lava_lamp',
	recipe = {
		{'default:obsidian','default:glass', 'default:obsidian'},
		{'default:obsidian','evenmoreblocks:lava_blob', 'default:obsidian'},
		{'default:obsidian','default:glass', 'default:obsidian'},
	}
})
minetest.register_craft({
	output = 'bucket:bucket_lava',
	recipe = {
		{'evenmoreblocks:lava_blob'},
		{'bucket:bucket_empty'},
	}
})
